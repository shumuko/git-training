Arnold Worldwide git and GitHub training
========================================

This is the readme file in markdown format.

## Step 1 ##
Sign up on github.com if you haven’t already.

## Step 2 ##

Download git, create an SSH key, connect your computer to github. You only need to do this once per computer so just follow this guide and forget about it when you’re done.

* OSX -- http://help.github.com/mac-set-up-git/
* Win -- http://help.github.com/win-set-up-git/

## Step 3 ##
Clone the training repository. The training repository is on GitHub here:

* https://github.com/davidosomething/Arnold-git-training

There's a text bar on that page with a git address:

    git@github.com:davidosomething/Arnold-git-training.git

Copy it and, in your terminal, clone the repository. Clone it into wherever you do your local web development, it'll create a
new folder (Arnold-git-training)

    git clone git@github.com:davidosomething/Arnold-git-training.git

## Step 4 ##
In the repository folder, create a new HTML file with your first initial last
name as the filename.
The file can be blank.

So for me, I'd create dotrakoun.html

## Step 5 ##
Add the file to your git index

    git add dotrakoun.html

Commit the file to your local repository with a commit message

    git commit -m "added my training file dotrakoun.html"

If you forget the "-m", you'll end up in a text editor where you'll have
to edit the commit message and save.

## Step 6 ##
Push the commit to your GitHub.

