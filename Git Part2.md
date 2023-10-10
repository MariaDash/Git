# Part 2.
+ [1. On local repository create branches:](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#1-on-local-repository-create-branches)

    [- Precondition](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#precondition)
    
    [- Working with branch creation](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#working-with-branch-creation)
    
+ [2. Push all branches to remote repository](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#2-push-all-branches-to-remote-repository)
+ [3. In Bug_Reports branch create a txt file with bugreport structure](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#3-in-bug_reports-branch-create-a-txt-file-with-bugreport-structure)
+ [4. Push the file to the remote repository](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#4-push-the-file-to-the-remote-repository)
+ [5. Merge Bug_Reports branch to main](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#5-merge-bug_reports-branch-to-main)
+ [6. Push main branch to remote repository](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#6-push-main-branch-to-remote-repository)
+ [7. In Checklists branch create file .txt with checklist structure](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#7-in-checklists-branch-create-file-txt-with-checklist-structure)
+ [8. Push the file to remote repository](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#8-push-the-file-to-remote-repository)
+ [9. On the remote repository make Pull request from Checklists branch to main](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#9--on-the-remote-repository-make-pull-request-from-checklists-branch-to-main)
+ [10. Sinchronize remote main branch and local main branch](https://github.com/MariaDash/Git/blob/main/Git%20Part2.md#10-sinchronize-remote-main-branch-and-local-main-branch)
## 1. On local repository create branches:
- Postman
- Jmeter
- CheckLists
- Bug_Reports
- SQL
- Charles_Proxy
- Mobile_Testing

### Precondition: 
1. Create remote repository Git ( at Github site)
2. Execute `git clone` command
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git
$ git clone https://github.com/MariaDash/Git.git
Cloning into 'Git'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git
$ 
```
3. Go to the directory "Git"
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git
$ cd Git
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$
```
4. Check you are connacted to correct remote repository
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git remote -v
origin  https://github.com/MariaDash/Git.git (fetch)
origin  https://github.com/MariaDash/Git.git (push)
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$
```
### Working with branch creation:
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git branch Postman
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git branch Jmeter
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git branch CheckLists
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git branch Bug_Reports
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git branch SQL
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git branch Charles_Proxy
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git branch Mobile_Testing
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git branch
  Bug_Reports
  Charles_Proxy
  CheckLists
  Jmeter
  Mobile_Testing
  Postman
  SQL
* main
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$
```
## 2. Push all branches to remote repository
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git push -u origin Postman
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Postman' on GitHub by visiting:
remote:      https://github.com/MariaDash/Git/pull/new/Postman
remote:
To https://github.com/MariaDash/Git.git
 * [new branch]      Postman -> Postman
branch 'Postman' set up to track 'origin/Postman'.
$Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git push -u origin Jmeter
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Jmeter' on GitHub by visiting:
remote:      https://github.com/MariaDash/Git/pull/new/Jmeter
remote:
To https://github.com/MariaDash/Git.git
 * [new branch]      Jmeter -> Jmeter
branch 'Jmeter' set up to track 'origin/Jmeter'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git push -u origin CheckLists
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'CheckLists' on GitHub by visiting:
remote:      https://github.com/MariaDash/Git/pull/new/CheckLists
remote:
To https://github.com/MariaDash/Git.git
 * [new branch]      CheckLists -> CheckLists
branch 'CheckLists' set up to track 'origin/CheckLists'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git push -u origin Bug_Reports
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Bug_Reports' on GitHub by visiting:
remote:      https://github.com/MariaDash/Git/pull/new/Bug_Reports
remote:
To https://github.com/MariaDash/Git.git
 * [new branch]      Bug_Reports -> Bug_Reports
branch 'Bug_Reports' set up to track 'origin/Bug_Reports'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git push -u origin SQL
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'SQL' on GitHub by visiting:
remote:      https://github.com/MariaDash/Git/pull/new/SQL
remote:
To https://github.com/MariaDash/Git.git
 * [new branch]      SQL -> SQL
branch 'SQL' set up to track 'origin/SQL'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git push -u origin Charles_Proxy
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Charles_Proxy' on GitHub by visiting:
remote:      https://github.com/MariaDash/Git/pull/new/Charles_Proxy
remote:
To https://github.com/MariaDash/Git.git
 * [new branch]      Charles_Proxy -> Charles_Proxy
branch 'Charles_Proxy' set up to track 'origin/Charles_Proxy'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git push -u origin Mobile_Testing
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Mobile_Testing' on GitHub by visiting:
remote:      https://github.com/MariaDash/Git/pull/new/Mobile_Testing
remote:
To https://github.com/MariaDash/Git.git
 * [new branch]      Mobile_Testing -> Mobile_Testing
branch 'Mobile_Testing' set up to track 'origin/Mobile_Testing'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$
```
Or you can push all at a time:
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$git push -u origin --all

Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$
```
## 3. In Bug_Reports branch create a txt file with bugreport structure
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git checkout Bug_Reports
Switched to branch 'Bug_Reports'
Your branch is up to date with 'origin/Bug_Reports'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (Bug_Reports)
$ vim bug_report.txt
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (Bug_Reports)
$ cat bug_report.txt
ID:1
Module: "LogIn"
Title: "Login" button disabled when pushing it after adding valid login & password
Test_Data:
    login:Adam;
    password:abc123
Pre-condition: user is registered
Env: Windows 10, Google Chrome 112, Firefox, Opera
STR: 1. Navigate to the site.com
     2. In the "login" block enter test data in "login" and "password" fields
     3. Push "Login" button
     4. "Login" button is disabled. No warning message.
ER: "Login" button is enabled, user log in.
AR: "Login" button is disabled. User can not log in.
Link_attach: Link
Bug_started:@me
Bug_Repro:@someone_else
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (Bug_Reports)
$
```
## 4. Push the file to the remote repository

```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (Bug_Reports)
$ git add . && git commit -m "add bugreport.txt"                                warning: in the working copy of 'bug_report.txt', LF will be replaced by CRLF the next time Git touches it
[Bug_Reports 6ddcb90] add bugreport.txt
 1 file changed, 17 insertions(+)
 create mode 100644 bug_report.txt
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (Bug_Reports)
$ git status
On branch Bug_Reports
Your branch is ahead of 'origin/Bug_Reports' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working tree clean
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (Bug_Reports)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 632 bytes | 316.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MariaDash/Git.git
   af23e16..6ddcb90  Bug_Reports -> Bug_Reports
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (Bug_Reports)
$
```
## 5. Merge Bug_Reports branch to main
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (Bug_Reports)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git merge Bug_Reports
Merge made by the 'ort' strategy.
 bug_report.txt | 17 +++++++++++++++++
 1 file changed, 17 insertions(+)
 create mode 100644 bug_report.txt
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ ls
README.md  bug_report.txt
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$
```
## 6. Push main branch to remote repository
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 338 bytes | 169.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MariaDash/Git.git
   3257c6b..773d45b  main -> main
branch 'main' set up to track 'origin/main'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$
```
## 7. In Checklists branch create file .txt with checklist structure
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git checkout CheckLists
Switched to branch 'CheckLists'
Your branch is up to date with 'origin/CheckLists'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (CheckLists)
$ vim checklist.txt
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (CheckLists)
$ cat checklist.txt
site           Firefox    Google Chrome       Opera
                version    version            version
Regisrtation
Email
Social media
Field validation
Authorisation
User logged in
User not logged in
Recovery password
Field Validation
Profile
Name change
Email change
Password change
Field Validation
Delete account
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (CheckLists)
$
```
## 8. Push the file to remote repository 
```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (CheckLists)
$ git add . && git commit -m "add checklist.txt"
warning: in the working copy of 'checklist.txt', LF will be replaced by CRLF the next time Git touches it
[CheckLists 271e82e] add checklist.txt
 1 file changed, 23 insertions(+)
 create mode 100644 checklist.txt
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (CheckLists)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 449 bytes | 224.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MariaDash/Git.git
   af23e16..271e82e  CheckLists -> CheckLists
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (CheckLists)
$
```
## 9.  On the remote repository make Pull request from Checklists branch to main
MariaDash merged 1 commit into main from CheckLists 1 minute ago

## 10. Sinchronize remote main branch and local main branch

```
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (CheckLists)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), 747 bytes | 93.00 KiB/s, done.
From https://github.com/MariaDash/Git
   773d45b..2ba4a43  main       -> origin/main
Updating 773d45b..2ba4a43
Fast-forward
 checklist.txt | 23 +++++++++++++++++++++++
 1 file changed, 23 insertions(+)
 create mode 100644 checklist.txt
Admin@DESKTOP-V6V9F0T MINGW64 /d/Testing_Course/Git/Git (main)
$
```
