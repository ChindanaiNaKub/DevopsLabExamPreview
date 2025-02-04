# DevopsLabExamPreview

1. Create the repository on your own computer

`git init -b main` - create git repo

`echo "This is a new file." > newfile.txt` - create newfile.txt with content

`git add filename` or `git add .` ( add all)

`git commit -m "Initial commit"`

2. Create the repository on the GitHub

`assume we know`

3. Open some repository, add a new file, and push the code to the remote repository

`cd path/to/your/repository`

`ข้อ 1`

`git remote add origin https://github.com/username/repo-name.git` - add remote to your local

`git push origin main` - push to remote ( github)

4. Create a new branch.

`git branch new-branch-name`

`git checkout -b new-branch-name` - create and witch to new branch

5. Create a tag and push it to the remote repository

`git tag v1.0`

`git push origin v1.0`

6. Create an issue, and then convert it to a task in a project

`do it yourself`

7. Create the task and assign it to yourself

`do it yourself`

8. Create a tag todo to the issue

`look it up`

9. Change the commit message in the previous commit

`git commit --amend -m "New commit message"`

10. Change the commit message for the older version.

`git rebase -i HEAD~5`

`Replace "pick" with "reword"`

11. Create a new project in GitHub and add a new column named “design”

`do it yourself`

12. Move the cursor to /var folder and return to the home folder

`cd /var`

`cd `

13. Change the permission of the file to 444

`chmod 444 filename`

14. Show the last 10 lines of the file name.csv

`tail -n 10 name.csv`

15. Show the path environment variable

`echo $PATH`

16. Show the CPU usage

`top`

`htop`
