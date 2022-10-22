# first
aliet@DESKTOP-CUDM853 MINGW64 ~
$ git config --global user.name 

aliet@DESKTOP-CUDM853 MINGW64 ~
$ git config --global user.name


aliet@DESKTOP-CUDM853 MINGW64 ~
$ git config --global user.email 

aliet@DESKTOP-CUDM853 MINGW64 ~
$ git config --global user.email


aliet@DESKTOP-CUDM853 MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/aliet/.git/

aliet@DESKTOP-CUDM853 MINGW64 ~ (master)
$ git add project1
fatal: pathspec 'project1' did not match any files

aliet@DESKTOP-CUDM853 MINGW64 ~ (master)
$ mkdir project1

aliet@DESKTOP-CUDM853 MINGW64 ~ (master)
$ cd project1

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ cat abc.txt
cat: abc.txt: No such file or directory

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ cat abc
cat: abc: No such file or directory

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ vim abc.txt

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ cat abc.txt
ii
hii iam balaji

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git add abc.txt
warning: in the working copy of 'project1/abc.txt', LF will be replaced by CRLF the next time Git touches it

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git init


aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        abc.txt

nothing added to commit but untracked files present (use "git add" to track)

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git add abc.txt
warning: in the working copy of 'abc.txt', LF will be replaced by CRLF the next time Git touches it

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git commit -m
error: switch `m' requires a value

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git commit -m "first update"
[master (root-commit) 3acf352] first update
 1 file changed, 2 insertions(+)
 create mode 100644 abc.txt

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git log
commit 3acf352c3ee47f85a7cabc579e43658ddbc32b2b (HEAD -> master)
Date:   Sat Oct 22 11:25:02 2022 +0530

    first update

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git remote add origin https://github.com/BalajigoudE/first.git

aliet@DESKTOP-CUDM853 MINGW64 ~/project1 (master)
$ git push origin master

