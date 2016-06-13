1. A new branch is used to work on each new feature.
2. The new branch is created using the command git checkout -b <name of branch>.
3. Files can be added and comitted to new branch similar to working on a new branch.
4. Once done, changes can be pushed to this branch using git push command.
5. After this user goes to github UI and issues a pull request to intimate other users that he has finished the changes.
6. Others review the code changes, there can be several back and forth.
7. Finally, the changes are merged into mainline using this sequence of commands.
	git checkout master
	git pull
	git pull origin <name of branch>
	git push
