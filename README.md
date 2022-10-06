Industry-Ready-Project-Tasks
Git and Github: 
Git is free and open source software for distributed version control. The version control system allows us to monitor and work together with our team members at the same workspace.

What is the meaning of version control?
Let’s suppose many developers are working together on a project and making changes simultaneously. Version control system can handle it in an efficient way as it maintains a history of all the changes which have happened in the past by any developer. Any time, a developer can revert the changes if required and can go back to previous version. Git is a distributed version control as the copy of full code is present in every developer’s local machine.

Task1: Git Commands -

1)	Configure user name and email in git:  It is important to configure your Git username and email address as every Git commit will use this information to identify you as the author.


2)	git init – This command is used to initialize the new working directory. 
 
You can see a new git repository is created with extension .git inside revision demo folder.

3)	git status- It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.
 
In the above case, we can see there is one modified file is present.

4)	git add file_name- This command adds a change in the working directory to the temporary staging area called index.
 

5)	git add .(dot) - This command track all the files in the working directory to the temporary staging area.
 

6)	git commit -m “commit message” – This command permanently store the contents of the index in the repository with git commit.
 

7)	git log – It lists the commits made in that repository in reverse chronological order; that is, the most recent commits show up first. As you can see, this command lists each commit with its SHA-1 checksum, the author’s name and email, the date written, and the commit message.  

8)	git branch - This command lists all the local branches in the current repository.

 

9)	git branch [branch_name] - This command creates a new branch.

 

10)	git branch –d [branch_name] - This command deletes the feature branch.

 

11)	 git checkout [branch_name] - This command is used to switch from one branch to another.

 

12)	git checkout –b [branch_name] - This command creates a new branch and also switches to it.

 

13)	 git remote add [variable_name] [remote_server_link] - This command is used to connect your local repository to the remote server.

 

14)	git push origin main- This command sends the branch commits to your remote repository.

 

15)	 git merge branch_name - This command merges the specified branch’s history into the current branch.

 
