In this readme file, useful git commands will be introduced.

# create a new repository on the command line
* echo "# testing" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git remote add origin https://github.com/jsrpy/testing.git
* git push -u origin master

# push an existing repository from the command line
* git remote add origin https://github.com/jsrpy/testing.git
* git push -u origin master

## Problems when creating new repo from command line
* You could possible run into error when trying to push your local files to your github repo, because there exists LICENCE.txt and some other stuff comes along with it.
* In such case run the following two lines to fast-forward the latest history to your local:

* git fetch
* git rebase origin/master

* You should now able to git push -u origin master
