# cloning-practice
This is for me to practice cloning repositories.

# clone the repository 
- git clone https://github.com/userName/repositoryName.git

# change directory to the cloned repository
- cd repositoryName

# change remote origin if necessary (can be avoided with forking a repository)
- git remote remove origin
- git remote add origin https://github.com/myUserName/newRepositoryName.git

# check the status of current files
- git status

# stage all changes
- git add .

# commit the changes with a message 
- git commit -m "commitMessage"

# push the changes to the remote repository (github)
- git push origin branchName
