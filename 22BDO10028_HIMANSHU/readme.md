2. The task
1.	View your config by running git config --list
step 1 - run command git config --list
2.	Add a new global alias
git config --global alias.lol 'log --oneline --graph --all'
This allows you to call git lol as an alternative to git log --oneline --graph --all
step 2 -  run command git config --global alias.lol 'log --oneline --graph --all'
 alias.lol 'log --oneline --graph --all' for setting a global alias.
3.	Run your alias git lol
step 3 - run command git lol 
4.	Run the full command git log --oneline --graph --all
Are there any difference in the output?
step 4 - run command git log --oneline --graph --all there will be no differences in the output.
5.	Create another alias, this time local, that lists commits where you are the author.
step 5 - run command git config --local alias.lome "log --author=\"$(git config --get user.name)\"" for setting a local alias.
6.	Run your alias git lome
What does it show?
step 6 - run command git lome.This should display the commits where you are the author.
7.	View your git config and its sources by running git config --list --show-origin
Can you find your alias configurations?
step 7 - run command git config --list --show-origin
This command will show the sources of your git configuration, including any aliases you've set.
8.	Try running git lome in a different git repository
Does it work?
step 8 - Yes, it should work, as the alias is set locally and should be available in any repository where it's been configured.
9.	Remove your git lol alias by running git config --global --unset alias.lol
step 9 - git config --global --unset alias.lol
This will remove the lol alias from your global git configuration.
