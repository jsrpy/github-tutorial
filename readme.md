# This repo contains tutorial to Git and particularly GitHub

Several important topics include:
1. [Git command (this readme)]()
2. [Licence Explained](licence_explanied.md)

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
You could possible run into error when trying to push your local files to your github repo, because there exists LICENCE.txt and some other stuff comes along with it.
In such case run the following two lines to fast-forward the latest history to your local:

* git fetch
* git rebase origin/master

You should now able to git push -u origin master

# The Correct Way

1. Create a repo on github webpage (with or without Licence & Readme files)
2. At your local drive, create a directory called 'repo' which shall be used to *sync* all works with github.
3. In command line, `git clone url` the SSH of your newly created repo.
4. You should see your new repo folder (~/repo/repo_name) downloaded and *sync* on your local drive.
5. Drop codes and files you wish to publish in that folder.
6. `git add *` > `git commit -m 'some message'` > `git push`
7. Refresh your github repo page and you should see your codes and files uploaded!
