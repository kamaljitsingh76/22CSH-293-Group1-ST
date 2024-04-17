[EVEN] The task

1.	View your config by running git config --list
   ![Screenshot 2024-04-17 100949](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/7242f74f-2345-437b-b0f3-cec9e8588e16)
2.	Add a new global alias
git config --global alias.lol 'log --oneline --graph --all'
This allows you to call git lol as an alternative to git log --oneline --graph --all
3.	Run your alias git lol
   ![Screenshot 2024-04-17 103139](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/f6436b68-d68a-4833-89d6-a8b217c8a092)
4.	Run the full command git log --oneline --graph --all
Are there any difference in the output?
![Screenshot 2024-04-17 103157](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/a01763f3-a3a2-45ff-93b8-d2eaa50a73ad)
5.	Create another alias, this time local, that lists commits where you are the author
git config --local alias.lome "log --author=\"$(git config --get user.name)\""
![Screenshot 2024-04-17 103357](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/d89f450f-f050-467f-b367-56ced2c8fbcd)
6.	Run your alias git lome
What does it show?
![Screenshot 2024-04-17 103454](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/94de11d7-7ac5-4d66-a688-984b5ca7ab8f)
7.	View your git config and its sources by running git config --list --show-origin
Can you find your alias configurations?
8.	Try running git lome in a different git repository
Does it work?
![Screenshot 2024-04-17 103535](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/18e8e423-4fe2-4059-8d23-d1497d6a6217)
9.	Remove your git lol alias by running git config --global --unset alias.lol
![Screenshot 2024-04-17 103608](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/6a7060f9-856a-4c81-8922-e04f119cca66)

![git_test1](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/82fb981a-a384-4328-96c7-8d2129170529)
![git_test2](https://github.com/ayush2442/22CSH-293-Group1-ST/assets/133507452/0c167c49-e583-4354-93f6-7ef4c48be67a)










