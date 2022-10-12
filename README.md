1. Created new Repository in Github name GitAndGithubReza

2. $ git clone https://github.com/sreza30th/GitAndGithubReza.git
    (Cloned repo GitAndGithubReza in local)
    (Changed directory to GitAndGithubReza by command cd cd GitAndGithubReza


3. $ git branch --show-current
   main ( Checked present working branch and found main branch)

4. Added Git.txt and Github.txt file by touch Git.txt and touch Github.txt
   command.
   checked the content of GitAndGithubReza by ls command.  

5. Added defination of Git to Git.txt file by nano Git.txt command
   Added defination of Github to Github.txt file by nano Github.txt command

6. nano README.md created README.md file and added all the codes used.

7. $ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Git.txt
        Github.txt
        README.md

nothing added to commit but untracked files present (use "git add" to track)
(checked changes by git status command)

8. Pushed the changes to remote by
     $ git add .
     $ git commit -m " Assign#5 1st commit" 
     $ git push -u origin main
Checked remote and found sreza30th Assign#5 1st commit added to repo.

9. $ mkdir temp (Made new directory name temp)
   Added a picture to temp file by

   sreza@REZA MINGW64 ~/GitAndGithubReza/temp (main)
   $ cd ..

  sreza@REZA MINGW64 ~/GitAndGithubReza (main)
  $ cd ..

  sreza@REZA MINGW64 ~ (master)
  $ ls
  
  sreza@REZA MINGW64 ~ (master)
  $ cd Pictures

  sreza@REZA MINGW64 ~/Pictures (master)
  $ ls
  'Camera Roll'/       'Saved Pictures'/   desktop.ini
   PictureDesktop.png   Screenshots/

  sreza@REZA MINGW64 ~/Pictures (master)
  $ cp PictureDesktop.png ~/GitAndGithubReza/temp

  sreza@REZA MINGW64 ~/Pictures (master)
  $ cd ~/GitAndGithubReza/temp

  sreza@REZA MINGW64 ~/GitAndGithubReza/temp (main)
  $ ls
  PictureDesktop.png

  sreza@REZA MINGW64 ~/GitAndGithubReza/temp (main)
  $

10. Went back to local directory and added file .gitignore  

     sreza@REZA MINGW64 ~/GitAndGithubReza/temp (main)
     $ cd ..

    sreza@REZA MINGW64 ~/GitAndGithubReza (main)
    $ touch .gitignore

11.Declared the temp folder in .gitignore file
    sreza@REZA MINGW64 ~/Reza_GitAndGithub (main)
    $ touch temp >>.gitignore

12. Checked local changes
    
    sreza@REZA MINGW64 ~/GitAndGithubReza (main)
    $ git status
    On branch main
    Your branch is up to date with 'origin/main'.

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
        .gitignore
        temp/

     nothing added to commit but untracked files present (use "git add" to track)
   
13.  Pushed the changes to remote by
     $ git add .
     $ git status
     $ git commit -m "Assign#5 after adding temp file to gitignore" 
     $ git push
     Checked remote and found sreza30th "Assign#5 after adding temp 
     file to gitignore" added to repo.

14.  sreza@REZA MINGW64 ~/GitAndGithubReza (main)
     $ git branch differences

     sreza@REZA MINGW64 ~/GitAndGithubReza (main)
     $ git branch
     differences
     * main

    sreza@REZA MINGW64 ~/GitAndGithubReza (main)
    $ git checkout differences
    Switched to branch 'differences'

15. Added features of Git to Git.txt and Github to Github.txt file 
    by nano command.

16. Created new file name differences.txt by nano command and added
    differences between Git and Github.

17. nano README.md added all the codes and steps used.

18. Checked the change by git status command

19.  Pushed the changes to remote by
     $ git add .
     $ git status
     $ git commit -m "Assign#5 push from differences branch" 
     $ git push origin differences
     Checked remote and found sreza30th "Assign#5 after adding temp 
     file to gitignore" added to repo.

20. In Remote main branch contains temp, .gitignore, Git.txt, Github.txt, README.md
   differences branch contains temp, .gitignore, Git.txt, Github.txt,
   README.md and difference.txt

21. sreza@REZA MINGW64 ~/GitAndGithubReza (differences)
    $ git checkout main
    Switched to branch 'main'
    Your branch is up to date with 'origin/main'.

    sreza@REZA MINGW64 ~/GitAndGithubReza (main)
    $ git merge differences
    Updating 2ea5e5e..b0fa339
    Fast-forward
    Git.txt        | 11 +++++++++++
    Github.txt     | 10 ++++++++++
    difference.txt | 15 +++++++++++++++
    3 files changed, 36 insertions(+)
    create mode 100644 difference.txt


22. No changes in remote branches.

23. sreza@REZA MINGW64 ~/GitAndGithubReza (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sreza30th/GitAndGithubReza.git
   2ea5e5e..b0fa339  main -> main

24. 17. nano README.md added all the codes and steps used.

25. suhai@Suhaira MINGW64 ~
    $ git clone --single-branch --branch differences https://github.com/sreza30th/GitAndGithubReza.git
    Cloning into 'GitAndGithubReza'...
    remote: Enumerating objects: 15, done.
    remote: Counting objects: 100% (15/15), done.
   remote: Compressing objects: 100% (13/13), done.
   remote: Total 15 (delta 3), reused 12 (delta 0), pack-reused 0
   Receiving objects: 100% (15/15), 1.48 MiB | 6.04 MiB/s, done.
   Resolving deltas: 100% (3/3), done.

   suhai@Suhaira MINGW64 ~
   $ cd GitAndGithubReza

    suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)

26. suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)
   $ nano Git.txt
   Added "This line is added by Suhaira" in Git.txt file.

27. sreza@REZA MINGW64 ~/GitAndGithubReza (main)
    $ nano Git.txt
    "Change done by Reza" added to Git.txt file under main branch.

28. suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)
$ git add .

suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)
$ git status
On branch differences
Your branch is up to date with 'origin/differences'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Git.txt


suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)
$ git comit -m "Changed By shoshirz"
git: 'comit' is not a git command. See 'git --help'.

The most similar command is
        commit

suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)
$ git push origin differences
Everything up-to-date

suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)
$ git commit -m "Changed By shoshirz"
[differences d967ed2] Changed By shoshirz
 1 file changed, 1 insertion(+)

suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)
$ git push origin differences
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/sreza30th/GitAndGithubReza.git
   b0fa339..d967ed2  differences -> differences

suhai@Suhaira MINGW64 ~/GitAndGithubReza (differences)

29. sreza@REZA MINGW64 ~/GitAndGithubReza (main)
$ git pull
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 4 (delta 2), reused 3 (delta 2), pack-reused 0
Unpacking objects: 100% (4/4), 910 bytes | 39.00 KiB/s, done.
From https://github.com/sreza30th/GitAndGithubReza
   b0fa339..a30b95d  main        -> origin/main
   b0fa339..d967ed2  differences -> origin/differences
Auto-merging Git.txt
CONFLICT (content): Merge conflict in Git.txt
Automatic merge failed; fix conflicts and then commit the result.

30.Git is free and open source distributed version control system designed to
handle everything from small to very large projevts with speed and efficiency

Features of Git

Tracks history.
Free and open source.
Supports non-linear development.
Creates backups.
Scalable.
Supports collaboration.
Branching is easier.
Distributed development.
<<<<<<< HEAD
Change done by Reza
=======
This Line is added by Suhaira
>>>>>>> a30b95dd189193a56f5b098b7d60993daa8893f1

31. sreza@REZA MINGW64 ~/GitAndGithubReza (main|MERGING)
$ git add .

sreza@REZA MINGW64 ~/GitAndGithubReza (main|MERGING)
$ git commit -m "conflict solved"
[main 35a1e20] conflict solved

sreza@REZA MINGW64 ~/GitAndGithubReza (main)

33. sreza@REZA MINGW64 ~/GitAndGithubReza (main)
$ git push
Enumerating objects: 13, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 8 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 1.88 KiB | 1.88 MiB/s, done.
Total 7 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To https://github.com/sreza30th/GitAndGithubReza.git
   a30b95d..35a1e20  main -> main
