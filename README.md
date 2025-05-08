Learn Git from feature-login

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
Check the Branch name of the Current Git folder
git branch
Note: You may see the branch as Master
* master

Step-10:
Rename the branch master to main (so that the names are consistent across Git and Github remote directory)
git branch -M master main

Step-11:
Check the Branch name of the Current Git folder
git branch
Note: You will see the following message
* main

Step-12:
 Checking the Status of Git local directory
 git status
 You will see a new message:
 On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Step-13:
Staging the files 
git add *

Step-14:
 Checking the Status of Git local directory
 git status
 You will see a new message:
 On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Step-15:
Committing the staged files
git commit -m "My First Commit"
Note: You will see a message something like the one below:
[main 3dd7301] My First Commit
 1 file changed, 48 insertions(+), 2 deletions(-)

Step-16:
Pusing the Change to remote directory
git push origin main
Note: You will see some message similar to the below one:
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 994 bytes | 994.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/NaveenSilvester/LearnGit.git
   17a9586..3dd7301  main -> main

Step-17:
Login to Git but and get to the repository LearnGit
You will see the README.md file updated into remote directory