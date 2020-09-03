/*
@ file: answers.md
@ author: Gabriel Havas
@ date: 09/03/2020
@ brief: git-lab answers
*/

Answer 1: git version 2.28.0.windows.1

Answer 2: diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
user.name=Gabriel Havas
user.email=gh641617@ohio.edu

Answer 3: When I type git --help, it gives a list of possible commands to use in certain situations and explains what each of them do

Answer 4: On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 6: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Answer 7: On branch master
nothing to commit, working tree clean

Answer 8: commit db8564e174f8eb26b0ebe43e5104606ab6f4b2d7 (HEAD -> master)
Author: Gabriel Havas <gh641617@ohio.edu>
Date:   Thu Sep 3 15:59:13 2020 -0400

    Initial commit

Answer 9: On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Answer 10: No the changes were not added to my local copy

Answer 11: To https://github.com/ghavas444/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/ghavas444/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12: Yes, once I performed git pull, the changes were made to my local copy

Answer 13: 
    Directory: C:\Users\Gabriel\desktop\cs2400\git-lab-2


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----         9/3/2020   4:23 PM            302 .gitignore
-a----         9/3/2020   4:23 PM             11 README.md
