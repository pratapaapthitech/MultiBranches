# MultiBranches
This MultiBranches shows how to handle multiple braches in github. And also manage the Dev,Stag and Master branches pull, merge and push operations.

- Create new repository with name example 'MultiBranches'.

- Clone this directory to local system using below Git Bash commands.
	- Switch to Directory on git bash - cd desktop then enter below commands.
		- git config --global user.name "xxxxxxxx"
		- git config --global user.email "xxxxxxxx"
		- git clone https://github.com/username/MultiBranches.git
	
- Create another branch like 'Development'.
	- git branch Development
	- git checkout Development
	
- Create and swith to new branch.
	git checkout -b Development
	
- Show all Braches.
	- git brach
	- git brach --list
	
- New braches push to git.
	- git push --set-upstream origin Development
	
- Show the status.
	- git status
	
- Update the files.
	- git pull
	
- Add files with comment and then Push.
	- git add .
	- git commit -m 'comment'
	- git push
	
- Show logs.
	- git log
	
- Merge the branches.
	- Switched to any brach
		- git checkout master
		- git merge Development
		- git push
		
- Remove brach.
	- git brach -d Development
	- git push origin :Development
	
	

