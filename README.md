### GIT

#Start
git config --global user.name "loginGithub" //init loginGithub
git config --global user.email "your@email" //init email

#Init project
git clone linksGithubRepository //copy remote repository
git init //local repository => git repository

#Push 
git add . (or -A) //Indexing change in local folder
git commit -m "name: commit"  // Create commit end fix change
git push origin master  //Push on the remote repository in the branch master

#Pull 
git pull origin master (or -f if errors)  //Return is remote repository in the local folders (fix change)
git fetch origin master //Return is remote repository in the local folders (no fix change)


