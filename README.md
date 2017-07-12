Creating a new repo
==================

So basically, to create a new repo:

1. Create a blank repo on github, e.g. repo

2. Create a new local folder for this repo (mkdir repohow)

3. Initialise empty repository in that folder (git init)

4.  Tell git that that's the repo that will go in this folder
git remote add origin https://github.com/silhouetted/repohow.git

5. Get what's in the repo by pulling it:

git pull <source> <branch>

git pull https://github.com/silhouetted/repohow.git master

In this instance this will download the README.md

6. Make changes - in this case I have changed the contents of README.md file

7. Update local git index - git add .

8. Then commit to local repo 

git commit -m "changing readme text"

9. Then push to github

First time will need:

git push --set-upstream origin master

10. Then after that just git push
 


