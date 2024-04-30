# Setup 
Git config --global user.name "darshan rana"
Git config --global user.email ranadarshan15@gmail.com
Git config –list

# Current working directory:
pwd

# To create a repository in the working directory, use the following commands:
mkdir Git_Demo
cd Git_Demo
pwd

# We will now initialize a repository to our folder.
Git init

#  let's check the status of the file that was created.
git status

# For Git to track that file, add command is used. If you know the exact name of the file, you can specify it and simply type the following command:
git add .

# The next step is to commit the file.
git commit -m "alpha"

# check all the information regarding the commits that were made.
git log

# push the two notepads on GitHub. Open your GitHub account, and create a new repository
git remote add origin Repo_URL
git remote -v
git push -u origin master





