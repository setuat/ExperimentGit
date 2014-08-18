https://www.youtube.com/watch?v=mYjZtU1-u9Y&index=1&list=PL1F56EA413018EEE1&src_vid=gKBiIWY7FYw&feature=iv&annotation_id=annotation_531330

1. Install the software with GIT Gui.
2. Change the Directory with which bash loads up
3.set the config for name and email 
git config --global  user.name "setu"
git config --global  user.email "setuat@yahoo.co.in"
4. now create a project in the folder we configured in step 2
5. git init <folder name>
it creates a git folder inside the project folder which is required by git
6.cd into <folder name>
7. git status 
8.get add . (add all files into local staging nothing has been committed to local git repository)
9.git rm --cached <file name>
10. git commit -m "<message>"
11. git log(will list all the log)
12. git diff 		  (to see the changes made in working directory w.r.t staging )
13. git diff --cached (to see the changes made in staging directory w.r.t local git repository)
14. shift +zz to exit log window
15. git log --oneline
16 git commit -a  -m "<message>" (directly add the working directory to local git repository skipping the staging )
17. git status -s (short message for the status)
18. ssh-keygen -t rsa -C "setuat@yahoo.co.in" (this generates a public and private key we need to add the public key to github.com to authenticate our remote machine)
19. ssh -T git@github.com (It will ask you for password. This will test the generated keys)
20. git remote add origin <ssh URL from git website> 
21. git push origin <branch name> (this will add the local git repository to remote git repository)
22. git config --list
23. git rm <file name> (this will remove the file from the repository)
24. git rm --cached <file name> (this remove the file from the repo and not delete it from the local file system )
25. git branch (this list all the branch for the repository)
26. git branch <name> (this will create a new branch with name )
27. git checkout <name> (switch to the other branch)
28. git clone <ssh link> (this will download the remote repository)
29. more to come