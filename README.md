- Git Command 

repo -> repository

clone -> bring a repo down from the internet (remote repository like Github) to your local machine

add -> track your files and changes with Git

commit -> save your changes into Git

push -> push your changes to your remote repo on Github (or another website)

pull -> pull changes down from the remote repo to your local machine

status -> check to see which files are being tracked or need to be commited

init -> use this command inside of your project to turn it into a Git repository and start using Git with that codebase




# Navigate to your project directory
cd /path/to/your/project

# Initialize Git (if not done yet)
git init

# Add file(s) to the staging area
git add newfile.txt

# Commit the file(s)
git commit -m "Added newfile.txt"

# Add GitHub remote repository (if not done yet)
git remote add origin https://github.com/your-username/your-repo.git

# Push the file to GitHub
git push -u origin master



-----------------------------------------------------------------------

#Rename the Local Branch
--git branch -m master main

#Push the main Branch to Remote:
--git push -u origin main

#Delete the Old master Branch:
--git push origin --delete master
