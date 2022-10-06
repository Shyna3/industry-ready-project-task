# Industry-Ready-Project-Tasks
## Git and Github: 
Git is free and open source software for distributed version control. The version control system allows us to monitor and work together with our team members at the same workspace.

## What is the meaning of version control?
Let’s suppose many developers are working together on a project and making changes simultaneously. Version control system can handle it in an efficient way as it maintains a history of all the changes which have happened in the past by any developer. Any time, a developer can revert the changes if required and can go back to previous version. Git is a distributed version control as the copy of full code is present in every developer’s local machine.

## Task1: Git Commands -

1)	**Configure user name and email in git**:  
It is important to configure your Git username and email address as every Git commit will use this information to identify you as the author.
![image](https://user-images.githubusercontent.com/106585670/194236051-478aabf2-52fe-4929-a922-bcf83ba0bb1b.png)

2)	**git init** – This command is used to initialize the new working directory. 
![image](https://user-images.githubusercontent.com/106585670/194236099-c76201a5-cfa1-4226-aabe-265838bf217f.png)
  You can see a new git repository is created with extension .git inside revision demo folder.

3)	**git status**- It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.
![image](https://user-images.githubusercontent.com/106585670/194236148-6c135685-552a-43cb-b02e-0bf76af71d48.png)
   In the above case, we can see there is one modified file is present.

4)	**git add file_name**- This command adds a change in the working directory to the temporary staging area called index.
![image](https://user-images.githubusercontent.com/106585670/194236181-fc1f64c9-1e2d-40c9-9bfd-218b8b499e54.png)
 

5)	**git add .(dot)** - This command track all the files in the working directory to the temporary staging area.
 ![image](https://user-images.githubusercontent.com/106585670/194236234-c372a852-4963-495a-b7ac-23d93335b1c3.png)

6)	**git commit -m “commit message”** – This command permanently store the contents of the index in the repository with git commit.
![image](https://user-images.githubusercontent.com/106585670/194236276-fee89699-1dec-494c-9393-5db48f76fd44.png)
 

7)	**git log** – It lists the commits made in that repository in reverse chronological order; that is, the most recent commits show up first. As you can see, this command lists each commit with its SHA-1 checksum, the author’s name and email, the date written, and the commit message.  
![image](https://user-images.githubusercontent.com/106585670/194236304-d8a74e75-d1ae-4048-a823-a8f7fd29fc6c.png)

8)	**git branch** - This command lists all the local branches in the current repository.
![image](https://user-images.githubusercontent.com/106585670/194236329-fdf3de82-dc5b-4b0f-af25-ace202050ab7.png)

 

9)	**git branch [branch_name]** - This command creates a new branch.
![image](https://user-images.githubusercontent.com/106585670/194236363-3901a0a2-78bc-4072-a3b0-bbbd1f99aba6.png)

 

10)	**git branch –d [branch_name]** - This command deletes the feature branch.
![image](https://user-images.githubusercontent.com/106585670/194236390-6e63e5b1-b5cb-41a8-985c-36028c627096.png)

 

11)	 **git checkout [branch_name]** - This command is used to switch from one branch to another.
![image](https://user-images.githubusercontent.com/106585670/194236427-4f11b3a9-2138-4165-ba40-683ce40eef30.png)
 

12)	**git checkout –b [branch_name]** - This command creates a new branch and also switches to it.
![image](https://user-images.githubusercontent.com/106585670/194236459-e02131e9-5729-43f7-903f-e354e3c42307.png)
 

13)	 **git remote add [variable_name] [remote_server_link]** - This command is used to connect your local repository to the remote server.
![image](https://user-images.githubusercontent.com/106585670/194236503-cec54287-5ffd-41e2-befc-375951c43bf8.png)

 

14)	**git push origin main**- This command sends the branch commits to your remote repository.
![image](https://user-images.githubusercontent.com/106585670/194236544-85a13485-d21e-4f7f-bd8e-95ea224ce5e3.png)
 

15)	 **git merge branch_name** - This command merges the specified branch’s history into the current branch.
![image](https://user-images.githubusercontent.com/106585670/194236588-b36aafae-83d7-4afb-9ee6-42dd2345e6f8.png)
 
