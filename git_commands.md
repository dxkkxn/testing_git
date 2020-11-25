# Initiate dir as git
git init
#Commit changes
git commit -m "message"
#add all changes
git add .
#add one file changes
git add "name_file"
#See status
git status

#add repository
git remote add origin "repository name"

#link with rep
git branch -M main

#Push changes into repository
git push -u origin main

#Pull changes from
git pull origin main

#User and pasword
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
