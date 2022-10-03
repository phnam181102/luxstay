## How to push code to github

dir -> git status -> git add . -> git commit -m "" -> git push/ git push origin <branch-name>

## The first time use git

```
$ git init
$ git checkout -b <master>
$ git add .
$ git remote add origin https://github.com/phnam181102/DiscordBot.git
$ git commit -m ""
$ git push origin <master> || git push origin <master> --force
```

## Delete files in .gitignore

```
$ git rm -r --cached .
$ git add .
$ git commit -m ''
$ git push origin master
```
