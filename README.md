# b21-gitting-started

## Computer setup

Install tools:
- git: `sudo apt install git`
- curl: `sudo apt install curl`
- kdiff3: `sudo apt install kdiff3`
- Visual Studio Code: https://code.visualstudio.com/Download
- Node.js:

```bash
# install nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

# close and reopen terminal
# install node
nvm install 14.19.1
```

Setup git:
```bash
# configure diff tool
git config --global push.default simple
git config --global merge.tool kdiff3
```