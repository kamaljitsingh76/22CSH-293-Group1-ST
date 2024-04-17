**Aaryan - 22BDO10001 Surprise Test - 1**


![Aaryan_22BDO10001-ST,pg-1](https://github.com/Aaryan-2104/Aaryan_22BDO10001/assets/89840919/51106c9d-79f6-4868-a03d-017e50ae9e63)



![Aaryan_22BDO10001-ST,pg-2](https://github.com/Aaryan-2104/Aaryan_22BDO10001/assets/89840919/9c684b61-8723-465e-b7c3-c379aec788b1)





SET - ODD

Topic - You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git.

 QnA  


Ques-1 :Create a branch called greeting and switch to it
Ans-1: To create a branch, we use command git branch branch-name and to switching it, we use git checkout command Here, git branch greeting  git checkout greeting  


Ques2. Edit the greeting.txt to contain your favorite greeting 
Ans-2: To edit the file, we open with the help of vi editor and add data to it by entering I and then inserting the data Here, vi greeting.txt, then press i for insertion and add data  


Ques-3. Add greeting.txt files to the staging area 
Ans-3: To add the files to the staging area, we write git add . And add the files to the staging area  


Ques-4. Commit 
Ans-4: To commit the files, we use the command, git commit -m “Message”  


Ques-5. Switch back to the master branch 
Ans-5: To switchiong between branches, we use git checkout branch_name So, here git checkout master  


Ques-6. Create a file README.md with information about this repository 
Ans-6: To create file, vi README.md and add some data to it   


Ques-7. Add the README.md file to staging area and make the commit 
Ans-7:  To add to the staging area, we use git add file-name and commit using git commit -m “Message”  


Ques-8. What is the output of git log --oneline --graph --all? 
Ans-8: This will represent every commit supplied just on one line together with the seven digit SHA number and commit message.  


Ques-9. Diff the branches 
Ans-9: To see the differences between 2 branches, we use git diff branch1 branch2 So, here git diff master greeting  


Ques-10.	Merge the greeting branch into master 
Ans-10: To merge we use the command git merge -m “message” branch name  


Ques-11.	What is the output of git log --oneline --graph --all now? 
Ans-11: Now the merge commit with the message you have given with merging branch to master will appear on the top. 




Ouputs->>



<img width="1440" alt="Output-1" src="https://github.com/Aaryan-2104/Aaryan_22BDO10001/assets/89840919/117ad925-227f-42b9-b87d-aa543eff6555">



<img width="1440" alt="Output-2" src="https://github.com/Aaryan-2104/Aaryan_22BDO10001/assets/89840919/047f2e8b-39a1-4665-b66d-203c1fdfdd56">



<img width="1440" alt="Output-3" src="https://github.com/Aaryan-2104/Aaryan_22BDO10001/assets/89840919/424f0492-84f4-46bf-aca8-c3d402d45e26">







