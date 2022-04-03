# b21-gitting-started

## Computer setup

Install tools:
- git: `sudo apt install git`
- curl `sudo snap install curl`
- kdiff3: `sudo apt-get install kdiff3`
- Visual Studio Code: https://code.visualstudio.com/Download
- Node.js: 
```bash
# Get PPA from node source
cd ~
curl -sL https://deb.nodesource.com/setup_14.x -o /tmp/nodesource_setup.sh

# Review script
nano /tmp/nodesource_setup.sh

# Run script
sudo bash /tmp/nodesource_setup.sh

# install node
sudo apt install nodejs
```

Setup git:
```bash
# configure diff tool
git config --global push.default simple
git config --global merge.tool kdiff3

# setup your user
git config --global user.name "Mona Lisa"
git config --global user.email "email@example.com"
```

## Create App

Following tutorial: https://developer.bentley.com/tutorials/web-application-quick-start/

- Move to source directory: `cd ~/source/`
- Create sample app: `npx create-react-app your-app-name --template @itwin/web-viewer --scripts-version @bentley/react-scripts`