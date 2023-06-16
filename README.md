# Dream
Clone the repository at https://github.com/KBCNMU
$ git --version
$ git --help
$ git clone https://github.com/Dhanshri1930/KBCNMU19.git

Use git add to add that file to the repository.use git commit to commit your change.
 git clone https://github.com/Dhanshri1930/Nikita.git
$ cd Nikita
$ touch Dhanu.txt
$ git status
$ git add Dhanu.txt
$ git commit -m "I'm Dhanshri"

use git push to get your parteners change into your repository verify that you have the new files.
$ git clone https://github.com/Dhanshri1930/Nikita.git
$ cd Nikita
$ touch Dhanu.txt
$ git status
$ git add Dhanu.txt
$ git commit -m "I'm Dhanshri"
$ git push -u origin main

Use git pull to get your partners change into your repository.Verify that you have the new files.
$ cd Project4
$ git init Project4
$ git pull https://github.com/Surendra1410/Project4.git

Use git log or git log | less to see a list of changes to the repository.
$ cd Project4
$ git log
$ git log --oneline
$ git log --stat
$ git log --patch
$ git log --graph
$ git log --graph --oneline
$ git log --after="2023-04-18"
$ git log --author="Surendra1410"
$ git log --author="surendrasavale928@gmail.com"
$ git log --grep="Hii I am Aashish"

Use git branch to create a new branch and git checkout to switch to the branch.
$ git clone https://github.com/Surendra1410/KBCNMU.git
$ cd KBCNMU
$ git branch Surendra
$ git checkout Surendra
$ touch file.txt
$ git add file.txt
$ git status
$ git commit -m "No Subject "
$ git push -u origin Surendra

Use git merge to merge you changes to the primary branch.
$ git clone https://github.com/Surendra1410/Dream.git
$ cd Dream
$ touch Dream1.txt
$ git add Dream1.txt
$ git commit -m " I am Sorry "
$ git branch Surendra
$ git checkout main
$ git checkout Surendra
$ touch Dream2.txt
$ git add Dream2.txt
$ git commit -m " thanks you "
$ git merge main
$ git status
$ git branch --list
$ git checkout Surendra
$ git checkout main
$ git checkout Surendra
$ git merge main

Demonstrate the use of git diff command.
$ git clone https://github.com/Surendra1410/Dream.git
$ cd Dream
$ git diff
$ git diff --color-words
$ git branch Surendra
$ git checkout Surendra
$ touch Drama.txt
$ git add Drama.txt
$ git commit -m " Hi "
$ git diff main Surendra
$ git diff main Surendra --name-only
$ git diff main
$ git diff main...Surendra
