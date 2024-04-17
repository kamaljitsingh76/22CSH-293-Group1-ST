SET-1
Question- You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git.
Step-1 Create a branch called greeting and switch to it
$ git checkout -b greeting

Step-2 Edit the greeting.txt to contain your favorite greeting
$ vim greeting.txt 
(in the text editor) Hello!

Step-3 Add greeting.txt files to the staging area
$ git add greeting.txt

Step-4 Commit
$git commit -m "Added favourite greeting"

Step-5 Switch back to the master branch
$ git checkout master

Step-6 Create a file README.md with information about this repository
$ touch README.md
$ vim README.md

Step-7 Add the README.md file to staging area and make the commit
$git add README.md
$ git commit "Adding the README file"

Step-8 What is the output of git log --oneline --graph --all?
"* hashcode (master) Adding the README file
* | hashcode (greeting) Added favourite greeting"

Step-9 Diff the branches
$ git diff master greeting

Step-10 Merge the greeting branch into master
$ git merge greeting

Step-11 What is the output of git log --oneline --graph --all now? Observe the extra merge commit created with the message "Merge branch 'greeting'".
"* hashcode (master) Merge branch greeting
| \
| * hashcode (master) Adding the README file
* | hashcode (greeting) Added favorite greeting"
