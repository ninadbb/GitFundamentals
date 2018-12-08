## Git Fundamentals

### Git Config

* List global configs:  
`$ git config --global --list`

* List local configs (insider repo):  
`$ git config --local --list`

* Setting configs  
`$ git config --global user.email "username@gmail.com"`

* Example configs:
```
$ git config --global -l
user.name=username
user.email=username@gmail.com
gui.recentrepo=C:/Users/username/Documents/workspace-sts-3.9.3.RELEASE/GitFundamentals
core.editor=vi
core.autocrlf=true
help.autocorrect=1
```


### Git Local

* create local repo:  
`$ git init`

* show status like pending/untracked files:  
`$ git status`

* track all file / add all files to local repo staging  
`$ git add .`

* add specific file  
`$ git add <filename>`

* add all updated files  
`$ git add -u`

* add all files including untracked  
`$ git add -A`

* Make local commit to repo  
`$ git commit -m "Inline Message For Commit"`

* check logs  
`$ git log `

* Do diff between two history  
`$ git diff  0ac911..9ec2b35`

* checkout file from repo - it may overide current changes  
`$ git checkout <filename>`

* reset revert all changes present in local to match with head/latest revision from local repo  
`$ git reset --hard`

* clean working copy  
`$ git clean`  
`$ git clean -f`

* ignore file to ignore directories or files from tracking  
` .gitignore`

### Git Remote
* Cloning remote repo  
`$ git clone https://github.com/jquery/query.git `

* Fetching from remote  
`$ git remote add origin https://github.com/username/GitFundamentals.git`  
`$ git fetch`  
`$ git fetch origin`  

* Pulling from remote  
`$ git pull`

* Pushing to remote  
`& git push`

