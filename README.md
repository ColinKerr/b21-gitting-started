# b21-gitting-started

## Computer setup

Install tools:
- git: `sudo apt install git`
- kdiff3: `sudo apt install kdiff3`
- Visual Studio Code: https://code.visualstudio.com/Download
- Node.js: `sudo snap install node --classic --channel=14`

Setup git:
```bash
# configure diff tool
git config --global push.default simple
git config --global merge.tool kdiff3
```