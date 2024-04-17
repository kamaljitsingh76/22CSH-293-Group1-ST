# Harsh Raj Singh (EVEN Set)
## Hard Copy Solution

![](firstpage.jpg)

![](secondpage.jpg)

### (Q.1)View your config by running git config --list

![](1.png)

### (Q.2)Add a new global alias
### git config --global alias.lol 'log --oneline --graph --all'
### This allows you to call git lol as an alternative to git log --oneline --graph --all

![](2.png)

### (Q.3) Run your alias git lol
![](3.png)

### (Q.4) Run the full command git log --oneline --graph --all
### Are there any difference in the output?
![](4.png)

### (Q.5) Create another alias, this time local, that lists commits where you are the author
### git config --local alias.lome "log --author=\"$(git config --get user.name)\""
![](5.png)

### (Q.6) Run your alias git lome
### What does it show?

![](6.png)


### (Q.7) View your git config and its sources by running git config --list --show-origin
### Can you find your alias configurations?

![](7.png)

### (Q.8) Try running git lome in a different git repository
### Does it work?

![](8.png)

### (Q.9) Remove your git lol alias by running git config --global --unset alias.lol

![](9.png)
