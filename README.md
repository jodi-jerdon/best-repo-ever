# best-repo-ever

# 2025-07-25 JJ 
# New Text for ReadMe file; copy of output from Git Bash.  


jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git config --global core.autocrlf true

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git branch
* main

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git branch myfeaturebranch

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git checkout myfeaturebranch
Switched to branch 'myfeaturebranch'

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git status
On branch myfeaturebranch
nothing to commit, working tree clean

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$

# 2025-07-25 09:24 JJ
# UPDATE START

$ git status
On branch myfeaturebranch
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git add README.md

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git status
On branch myfeaturebranch
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git restore README.md

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git status
On branch myfeaturebranch
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git restore --staged README.md

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git status
On branch myfeaturebranch
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git add README.md

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git status
On branch myfeaturebranch
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git commit -m "My first commit"
[myfeaturebranch 67762a8] My first commit
 1 file changed, 27 insertions(+), 1 deletion(-)

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git status
On branch myfeaturebranch
nothing to commit, working tree clean

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git push -u origin myfeaturebranch
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 24 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 501 bytes | 501.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'myfeaturebranch' on GitHub by visiting:
remote:      https://github.com/jodi-jerdon/best-repo-ever/pull/new/myfeaturebranc
remote:
To https://github.com/jodi-jerdon/best-repo-ever.git
 * [new branch]      myfeaturebranch -> myfeaturebranch
branch 'myfeaturebranch' set up to track 'origin/myfeaturebranch'.

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git chekout main
git: 'chekout' is not a git command. See 'git --help'.

The most similar command is
        checkout

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (myfeaturebranch)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 911 bytes | 303.00 KiB/s, done.
From https://github.com/jodi-jerdon/best-repo-ever
   06ccff6..417298e  main       -> origin/main
Updating 06ccff6..417298e
Fast-forward
 README.md | 28 +++++++++++++++++++++++++++-
 1 file changed, 27 insertions(+), 1 deletion(-)

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git branch new-branch-1

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git checkout -b new-branch-1
fatal: a branch named 'new-branch-1' already exists

jodi_jerdon@C28NCX3 MINGW64 ~/best-repo-ever (main)
$ git checkout new-branch-1
Switched to branch 'new-branch-1'

# UPDATE END
