![WhatsApp Image 2024-04-17 at 10 14 35_6d8973d1](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/655dc479-8b67-4657-b77e-f50abe8b8e69)
![WhatsApp Image 2024-04-17 at 10 14 35_396067ae](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/eddfc09d-9896-4568-a30b-1afaa46ea746)
![WhatsApp Image 2024-04-17 at 10 14 34_78b7575e](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/14397b03-f104-4f43-a990-b98012368529)
1.	View your config by running git config --list
![Screenshot 2024-04-17 102122](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/523c8009-3502-43aa-b07f-2b5f00d356c3)

2.	Add a new global alias
git config --global alias.lol 'log --oneline --graph --all'
This allows you to call git lol as an alternative to git log --oneline --graph --all
![Screenshot 2024-04-17 102134](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/bea39306-61ad-4635-8bba-89a2747ed020)

3.	Run your alias git lol
   ![Screenshot 2024-04-17 102143](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/a880aa35-d67e-4e78-936e-8a5b721f8b54)

4.	Run the full command git log --oneline --graph --all
Are there any difference in the output?
![Screenshot 2024-04-17 102152](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/e280569b-3da7-4cc7-b236-286720bdafeb)
NO there's no difference.
5.	Create another alias, this time local, that lists commits where you are the author
git config --local alias.lome "log --author=\"$(git config --get user.name)\""
![Screenshot 2024-04-17 102201](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/6e94dfc7-d63b-42b6-99d1-f66d08a5467c)

6.	Run your alias git lome
What does it show?
![Screenshot 2024-04-17 102209](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/2c0a8c96-4e51-470a-8a15-e9bb547d0a28)

7.	View your git config and its sources by running git config --list --show-origin
Can you find your alias configurations?
![Screenshot 2024-04-17 102219](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/3ea3968e-bd32-4bcf-b53d-751ee574fe21)
yes, it shows alias configurations.
8.	Try running git lome in a different git repository
Does it work?
![Screenshot 2024-04-17 102244](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/c1b8e3e8-f27c-46c0-b5cd-2a2a44aaad8f)
NO
9.	Remove your git lol alias by running git config --global --unset alias.lol
![Screenshot 2024-04-17 102227](https://github.com/Sushantjha1236/22CSH-293-Group1-ST/assets/113833084/636efd67-87f0-4720-94c8-41acf433414e)

 
