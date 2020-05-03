# GitTest

#### INITIALIZE A REPOSITORY FROM EXISTING CODE
`git init`

#### BEFORE FIRST COMMIT
`git status`

#### ADD GITIGNORE FILE

#### ADD FILES TO STAGING AREA
`git add .  #add all files`

#### REMOVE FILES FROM STAGING AREA
`git reset`

#### REVERTING LOCAL UNPUSHED COMMITS
`git reset --hard origin/<your-branch-name>  #COMPLETE REMOVAL`  
`git reset --soft origin/<your-branch-name>  #ONLY REMOVES THE COMMIT NOT THE FILES`  

#### OUR FIST COMMIT
`git commit -m "First Commit"`

#### CLONING A REMOTE REPO
`git clone <url> <whereToClone>`

#### VIEWING INFORMATION ABOUT REMOTE REPO
`git remote -v`
`git branch -r`

#### PUSHING CHANGES
###### commit changes
`git diff`
`git status`
`git add .`
`git commit -m "CommitMessage"`
###### then push
`git pull origin <branch>`
`git push origin <branch>`

#### CREATE A BRANCH FOR DESIRED FEATURE
`git branch <branchname>`
`git checkout <branchname>`
`git add . `
`git comment -m "commitMessage"`

#### PUSH BRANCH TO REMOTE
`git push -u origin <branchname>`
`git branch -a`

#### MERGE A BRANCH
`git checkout master`
`git pull origin master`
`git branch --merged`
`git merge <branchname>`
`git push origin master`

#### DELETING A BRANCH
`git branch --merged`
`git branch -d <branchname>`
`git branch -a`
`git push origin --delete <branchname.`
