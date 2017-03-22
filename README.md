# demo_repo
first repository for demo purpose


Vinit@admin-PC MINGW32 /c/sandbox/demo_git
$ git init
Initialized empty Git repository in C:/sandbox/demo_git/.git/

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls -lart
total 4
drwxr-xr-x 1 Vinit 197121 0 Mar 22 13:00 ../
drwxr-xr-x 1 Vinit 197121 0 Mar 22 13:00 ./
drwxr-xr-x 1 Vinit 197121 0 Mar 22 13:00 .git/

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ touch text1.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ touch text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls
text1.txt  text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        text1.txt
        text2.txt

nothing added to commit but untracked files present (use "git add" to track)

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git add .

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   text1.txt
        new file:   text2.txt


Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit -m "first commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Vinit@admin-PC.(none)')

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git config --global user.email "rajbirs4ever@gmail.com"

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git config --global user.name "rajbirsood"

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit -m "first commit"
[master (root-commit) 3fdce5d] first commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 text1.txt
 create mode 100644 text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git status
On branch master
nothing to commit, working tree clean

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git log
commit 3fdce5d0a1714091d6b07a95432dfe34aee5f8c7
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:02:53 2017 +0530

    first commit

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$


Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$


Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ vi text1.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   text1.txt

no changes added to commit (use "git add" and/or "git commit -a")

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git add .
warning: LF will be replaced by CRLF in text1.txt.
The file will have its original line endings in your working directory.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   text1.txt


Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit -m "text1.txt modified"
[master 567f0ef] text1.txt modified
 1 file changed, 1 insertion(+)

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls
text1.txt  text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git log
commit 567f0ef313dd1d447d4c36f164f4000dad0b1673
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:04:00 2017 +0530

    text1.txt modified

commit 3fdce5d0a1714091d6b07a95432dfe34aee5f8c7
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:02:53 2017 +0530

    first commit

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git checkout -b testbr
Switched to a new branch 'testbr'

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git branch
  master
* testbr

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ vi text
text1.txt  text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ vi text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git status
On branch testbr
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   text2.txt

no changes added to commit (use "git add" and/or "git commit -a")

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git add .
warning: LF will be replaced by CRLF in text2.txt.
The file will have its original line endings in your working directory.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git commit -m "text2.txt modified"
[testbr 6e4189f] text2.txt modified
 1 file changed, 1 insertion(+)

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git log
commit 6e4189fbf2b7e9ab21e9c89e764f48e1d6b0d30f
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:05:15 2017 +0530

    text2.txt modified

commit 567f0ef313dd1d447d4c36f164f4000dad0b1673
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:04:00 2017 +0530

    text1.txt modified

commit 3fdce5d0a1714091d6b07a95432dfe34aee5f8c7
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:02:53 2017 +0530

    first commit

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git checkout master
Switched to branch 'master'

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git log
commit 567f0ef313dd1d447d4c36f164f4000dad0b1673
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:04:00 2017 +0530

    text1.txt modified

commit 3fdce5d0a1714091d6b07a95432dfe34aee5f8c7
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:02:53 2017 +0530

    first commit

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls
text1.txt  text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ cat text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git merge testbr
Updating 567f0ef..6e4189f
Fast-forward
 text2.txt | 1 +
 1 file changed, 1 insertion(+)

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls
text1.txt  text2.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ cat text2.txt
text2.txt modified

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git remote add origin https://github.com/rajbirsood/demo_repo.git

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git push -u origin master
Username for 'https://github.com': rajbirsood
Counting objects: 9, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 735 bytes | 0 bytes/s, done.
Total 9 (delta 0), reused 0 (delta 0)
To https://github.com/rajbirsood/demo_repo.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git checkout testbr
Switched to branch 'testbr'

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git push
fatal: The current branch testbr has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin testbr


Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git push --set-upstream origin testbr
Username for 'https://github.com': rajbir.sood
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/rajbirsood/demo_repo.git/'

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git push --set-upstream origin testbr
Username for 'https://github.com': rajbirsood
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/rajbirsood/demo_repo.git
 * [new branch]      testbr -> testbr
Branch testbr set up to track remote branch testbr from origin.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ cd ..

Vinit@admin-PC MINGW32 /c/sandbox
$ ls
demo_git/

Vinit@admin-PC MINGW32 /c/sandbox
$ git clone https://github.com/edureka-git/devops.git
Cloning into 'devops'...
remote: Counting objects: 80, done.
remote: Total 80 (delta 0), reused 0 (delta 0), pack-reused 80
Unpacking objects: 100% (80/80), done.

Vinit@admin-PC MINGW32 /c/sandbox
$ ls
demo_git/  devops/

Vinit@admin-PC MINGW32 /c/sandbox
$ cd devops/

Vinit@admin-PC MINGW32 /c/sandbox/devops (master)
$ ls
addressbook_screenshot.png  build.properties  build.xml  pom.xml  README.md  src/

Vinit@admin-PC MINGW32 /c/sandbox/devops (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/devops (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/devops (master)
$ pwd
/c/sandbox/devops

Vinit@admin-PC MINGW32 /c/sandbox/devops (master)
$ cd ..

Vinit@admin-PC MINGW32 /c/sandbox
$ ls
demo_git/  devops/

Vinit@admin-PC MINGW32 /c/sandbox
$ cd demo_git/

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git branch
  master
* testbr

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ touch text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git add text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit text3.txt
Aborting commit due to empty commit message.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit -m "3rd file added"
[master 490db28] 3rd file added
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ vi text1.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit -m "text1.txt modificatio added"
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
Changes not staged for commit:
        modified:   text1.txt

no changes added to commit

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git push
Username for 'https://github.com': rajbirsood

Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 295 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/rajbirsood/demo_repo.git
   6e4189f..490db28  master -> master

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls
text1.txt  text2.txt  text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git push origin master
Username for 'https://github.com': rajbirsood
Everything up-to-date

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   text1.txt

no changes added to commit (use "git add" and/or "git commit -a")

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls
text1.txt  text2.txt  text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git add text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit -m "3rd file added again"
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
        modified:   text1.txt

no changes added to commit

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   text1.txt

no changes added to commit (use "git add" and/or "git commit -a")

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit -m "text1.txt modified"
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
        modified:   text1.txt

no changes added to commit

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ ls
text1.txt  text2.txt  text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git log
commit 490db28db5decdcdfb1e3eac4a09ce4f9db5d866
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:25:35 2017 +0530

    3rd file added

commit 6e4189fbf2b7e9ab21e9c89e764f48e1d6b0d30f
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:05:15 2017 +0530

    text2.txt modified

commit 567f0ef313dd1d447d4c36f164f4000dad0b1673
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:04:00 2017 +0530

    text1.txt modified

commit 3fdce5d0a1714091d6b07a95432dfe34aee5f8c7
Author: rajbirsood <rajbirs4ever@gmail.com>
Date:   Wed Mar 22 13:02:53 2017 +0530

    first commit

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git diff
warning: LF will be replaced by CRLF in text1.txt.
The file will have its original line endings in your working directory.
diff --git a/text1.txt b/text1.txt
index 491a7bb..39d5023 100644
--- a/text1.txt
+++ b/text1.txt
@@ -1 +1,2 @@
 first file modified
+some changes

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   text1.txt

no changes added to commit (use "git add" and/or "git commit -a")

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git add text1.txt
warning: LF will be replaced by CRLF in text1.txt.
The file will have its original line endings in your working directory.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git commit -m "text1.txt modified"
[master 39b99e2] text1.txt modified
 1 file changed, 1 insertion(+)

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git push
Username for 'https://github.com': rajbirsood
Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 332 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/rajbirsood/demo_repo.git
   490db28..39b99e2  master -> master

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$ git checkout testbr
Switched to branch 'testbr'
Your branch is up-to-date with 'origin/testbr'.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git pull origin/master
fatal: 'origin/master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git pull master
fatal: 'master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git merger master
git: 'merger' is not a git command. See 'git --help'.

Did you mean this?
        merge

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git merge master
Updating 6e4189f..39b99e2
Fast-forward
 text1.txt | 1 +
 text3.txt | 0
 2 files changed, 1 insertion(+)
 create mode 100644 text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ ls
text1.txt  text2.txt  text3.txt

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ cat text1.txt
first file modified
some changes

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (testbr)
$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

Vinit@admin-PC MINGW32 /c/sandbox/demo_git (master)
$
