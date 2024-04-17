# 22BDO10019 - Surprise Test

**This belongs to Yash Dwivedi**

1. **UId :** 22BDO10019
2. **Section :** 22BCD-1(A)
3. **Set :** Odd

**Questions and Answers**

1. *Create a branch called greeting and switch to it*

   * git checkout -b greeting
  
   ![One](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/one.png)
   
2. Edit the greeting.txt to contain your favorite greeting

   * gedit greeting.txt
  
    ![One](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/two.png)
   
3. Add the greeting.txt file to the staging area

   * git add greeting.txt
  
     ![One](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/three.png)
   
4. Commit

   * git commit -m "Add the greeting in greeting.txt"
  
     ![One](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/four.png)
   
5. Switch back to the master branch, create a file README.md with information about this repository

   * git checkout master
   * gedit README.md
  
6. Add the README.md file to the staging area and make the commit 

   * git add README.md
   * git commit -m "Updated README.md"
  
    ![One](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/five.png)
   
7. What is the output of git log --oneline --graph --all?

   * git log --oneline --graph --all
  
     ![One](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/six.png)
   
8. Diff the branches

   * git diff master greeting
  
    ![One](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/seven.png)
   
9. Merge the greeting branch into master

   * git merge greeting
   
   *Updating c8cc33e..c72fff5*
   
   *Fast-forward*
   
   *README.md | 51 +++++++++++++++++++++++++++++++++++++++++++++++++++*
   
   *1 file changed, 51 insertions(+)*
   
   *create mode 100644 README.md*
   
10. What is the output of git log --oneline --graph --all now? Observe the extra merge commit created with the message "Merge branch 'greeting'".

    * The extra merge commit is created during the merge process because the merge operation combines the data of the greeting branch into master branch and created a new commit
   

**Suprise Test Sheet**

![one](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/ss-1.png)

![two](https://github.com/Tempestyash123456/22CSH-293-Group1-ST/blob/main/ss-2.png)
