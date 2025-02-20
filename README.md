# DevopsLabExamPreview

1. Create the repository on your own computer

`git init -b main` - create git repo

2. Create the repository on the GitHub

`assume we know`

3. Open some repository, add a new file, and push the code to the remote repository

`cd path/to/your/repository`

`echo "This is a new file." > newfile.txt` - create newfile.txt with content

`git add filename` or `git add .` ( add all)

`git commit -m "Initial commit"`

`git remote add origin https://github.com/username/repo-name.git` - add remote to your local

`git fetch origin` - fetch the remote changes

`git pull origin main --rebase` - pull changes

`git push -u origin main` - push to remote ( github)

4. Create a new branch.

`git branch new-branch-name`

`git checkout -b new-branch-name` - create and witch to new branch

5. Create a tag and push it to the remote repository

`git tag v1.0`

`git push origin v1.0`

6. Create an issue, and then convert it to a task in a project

![alt text](image.png)

`สร้าง issue -> ไป project (blank) -> ทำแบบในรูป`

7. Create the task and assign it to yourself

![alt text](image-1.png)

8. Create a tag todo to the issue

![alt text](image-2.png)

`Todo ตัวเขียวๆ ใน status`

9. Change the commit message in the previous commit

`git commit --amend -m "New commit message"`

10. Change the commit message for the older version.

`git rebase -i HEAD~5`

`กด i เป็น insert mode`

`Replace "pick" with "reword"`

`กด :wq`

`เปลื่ยน commit message`

`:wq เสร็จ`

`เช็คด้วย git log`

11. Create a new project in GitHub and add a new column named “design”

![alt text](image-3.png)

`กดติ้กถูกแล้วสร้าง Design`

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
