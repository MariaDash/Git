# Git 
## Homework 1.:
## 1. https://github.com/MariaDash/Json
## 2. https://github.com/MariaDash/XML
## 3. https://github.com/MariaDash/TXT
## Homework 2.:
## 1. On local repository create branches:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
Precondition: 
1. Create remote repository Git ( at Github site)
2. Execute git clone command
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
Working with branch creation:
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
