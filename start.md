# Getting Started

Terminal:  The generic term for a text based user interface on a computer.  Text based commands are entered using the keyboard and the response to the command is displayed as new lines of text.  It is a powerful tool that will be used regularly in this class.

To open the terminal on your laptop:

1. Click on the icon in the upper left.
2. Type `terminal` in the search bar
3. Select `Terminal Emulator`

Alternatively type `Ctrl-Alt-T`

To execute a command:

1. Type a command (Try `ls` without the quotes)
2. Hit return
The resulting text is the content of the current folder you are in.  You are in the home directory.

Here is a list of terms to get started.  Don’t worry if you don’t understand all the terms now, just remember their names.

- ls - lists the contents of the current folder
- cd - change directory … move from one folder to another ('cd ..' go up a directory.  'cd ~' go to home directory.
- mkdir - makes a folder
- touch - makes a file
- man - gives you the manual for a command
- sudo - lets you do things you are not otherwise allowed to do (http://xkcd.com/149/)
- git - github command line tool
- nano - text editor
- code - IDE we will use to create and test our code

## Setup Git with your user

```bash
# setup your user
git config --global user.name "Mona Lisa"
git config --global user.email "email@example.com"
```

## Create App

Following tutorial: https://developer.bentley.com/tutorials/web-application-quick-start/

- Move to source directory: `cd ~/source/`
- Create sample app: `npx create-react-app <your-app-name> --template @itwin/web-viewer --scripts-version @bentley/react-scripts`
