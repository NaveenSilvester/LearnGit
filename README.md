Learn Git

Step-1:
Create a Repository in Git Hub
Lets Create a Repo named LearnGit
The remote url for the LearnGit is: https://github.com/NaveenSilvester/LearnGit.git

Step-2:
Create a folder in your local computer and name it as LearnGit

Step-3:
Open Command Prompt and navigate into the newly created folder named LearnGit on your local computer

Step-4:
Initiate Git by typing the following command
git init
You will get a message stating
"Initialized empty Git repository in E:/NaveenLearnings2025/LearnGit/.git/"

Step-5:
Adding remote repo to local directory by typing this command on your local computer's command prompt
Note: You need to provide the git URL tha you obtained from Step-1
git remote add origin https://github.com/NaveenSilvester/LearnGit.git

Step-6:
Make a pull request from Remote directory so that local directory is in sync with the latest files in Remote dirctory
git pull origin main
Note: You will get some message like the below:
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 863 bytes | 3.00 KiB/s, done.
From https://github.com/NaveenSilvester/LearnGit
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main

 Step-7:
 View the Local Directory (LearnGit) and you will see the files from Remote directory copied into your local directory

 Step-8:
 Create a new file in your remote Directory and call the file as README.md
 Type some contents into this README.md file

 Step-9:
 Checking the Status of Git local directory
 git statu
 You will see a new message:
 