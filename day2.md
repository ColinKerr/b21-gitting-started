# Day Two

## Goals

- Sign up for itwin developer account at developer.bentley.com
- Confiure app created last time
  - Copy `.env` file and name it `.env.local` set variables needed to run in the `.env.local` file
- Increase number of file watchers
  - See current max: `cat /proc/sys/fs/inotify/max_user_watches`
  - Open file which controls max file watchers: `code /etc/sysctl.conf`
  - Scroll to the bottom and add: `fs.inotify.max_user_watches=524288`
  - Load changed config: `sudo sysctl -p`
  - Test to see if the max has changed: `cat /proc/sys/fs/inotify/max_user_watches`
- Run iTwin app
  - `npm install`
  - `npm run start` 
- Make some simple code modifications
  - Change title of page
  - Change theme to dark mode

## Extras

- Share GitHub and discord user names so I can invite to GitHub org and discord chat

## Stretch Goals
- Create GitHub repo for your app
- Upload local source to GitHub repo
  - Connect local repo to the repo you created: `git remote add origin <remote_repo_url>`
  - Add files: `git add .`
  - Commit files: `git commit -m"This is a commit message" -a`
  - Pull: `git pull`
  - Push your changes: `git push`