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
