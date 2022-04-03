# b21-gitting-started

## Computer setup

Install tools:
- git: `sudo apt install git`
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