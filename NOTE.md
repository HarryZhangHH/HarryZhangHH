## To push the file to github on Linux

To stage a file
```
  git status
  git init
  git add.
  git commit -m "upload"
  git status
```
Stage Files to Prepare for Commit

1. Enter one of the following commands, depending on what you want to do:
    Stage all files: ```git add .```
    Stage a file: ```git add example.html``` (replace example.html with your file name)
    Stage a folder: ```git add myfolder``` (replace myfolder with your folder path)
2. Check the status again by entering the following command:
```
  git status
```
3. You should see there are changes ready to be committed.


To unstage a file
  git reset HEAD example.html
 
If you made a mistake in your last commit message, run this command:
```
  git commit --amend -m "Put your corrected message here"
```
When viewing a list of commits, there are various commands depending on how much info you want to see.
    To see a simplified list of commits, run this command: ```git log --oneline```
    To see a list of commits with more detail (such who made the commit and when), run this command: ```git log```
    
    
```
git push origin my-branch
```
Username for 'https://github.com': myusername
Password for 'https://myusername@github.com': mypassword

remote: Invalid username or password.fatal: Authentication failed for 'https://github.com/my-repository’
Use the classic token to solve: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
