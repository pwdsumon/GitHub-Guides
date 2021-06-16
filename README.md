# GitHub Guides


## create a new repository on the command line
echo "# test" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git remote add origin https://github.com/pwd-sumon/GitHub-Guides.git  
git push -u origin master  

## Configure your Git username/email ( First Time Only )
git config --global user.name "username"
git config --global user.email "email"

## push an existing repository from the command line  
git remote add origin https://github.com/pwd-sumon/GitHub-Guides.git   
git push -u origin master   



| Git Command | Description |
|-------------|-------------|
| git clone id | All poroject Download |
| git init | First Time Only  |
| git add . | Your All Files Added |
| git add abc.txt | abc.txt file Added |
| git commit -m "Your Comment" yourfile.extension | For Specific File |
| git commit -m "Your Comment" x.txt a.html | For x.txt and a.html file adding |
| git commit -am "Your Comment" | For All File Commited |
| git diff | What changes |
| git log | For all working history from first day to last day  |
| git log x.txt | for x.txt working history |
| git show 2b0810c2d009af10f37eac32 | For specific work i am worked (2b0810c2d009af10f37eac32 every commit create ad new ID) |
| <kbd>Previous Committee Returns, Resets, amend</kbd>|
| git checkout 2b0810c2d009af10f37eac32 | Return to the previous task (2b0810c2d009af10f37eac32 work ID) |
| git checkout master | For again to move your last work |
| git checkout 2b0810c x.txt |  Return to the previous task x.tx (2b0810c work ID) |
| git checkout master -f | For only one file previous |
|<kbd>Worng Commit</kbd>|
| git commit -m "Accidental Commit" x.txt | The commit by mistake |
| git reset -soft 2b0810c | Soft Reset (The old commit will go away but the next commit will remain ) |
| git reset -hard 2b0810c | Hard Reset (The old commit will go away) |
|<kbd>That's what we did</kbd>|
| git reflog | That's what we did |
| git rm file1.txt | delete a file from a Git repository (first command) |
| git commit -m "remove file1.txt"  | (Second Command (finaly removed file  |
| git push origin master --forc or (short of force -f) git push origin master -f | If don't work git push -u origin master |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
