# hello-world
A project to learn how to use Git and GitHub with R.

Learning all of the things about this awesome collaborative version-control tool!

#big day! made a GitHub account, installed git with the terminal, and connected git to R. yay!


To get these local changes made in R onto github, use a commit-pull-push process.

1. First you "commit" the changes made in R to github.

2. Pull, using the down button in the right/git pane.
 
3. Then Push, using the down button in the right/git pane.


Detailed process to edit Github files in R:

#Log into your Github account and navigate to the repository for your work
#click clone or download and copy the link
#back in R, file -> newproject -> version control-> git, paste the HTTPS link from the Github repository into the repository url field
#Select a folder (e.g., desktop) on your computer - that is where the “local” copy of your repository will be (the online one being on Github).

#Once the files have finished copying across, you will notice that a few things about your RStudio session have changed.
#there is a Git tab in the top right corner of RStudio, and all the files that are in the repo are now on your computer as well.

#You are now ready to start making changes and documenting them through Github!
#click on a file name and begin editing.
#save locally to your repo folder.
#"stage" the file by clicking the "staged" column in the right pane.
#now we're ready to commit to github;
#clickon commit tab in the right pane and add a commit message; aim to be concise and informative - what did you do? 

#Once you have clicked on commit you will get a message about the changes you have made.
#Changes made locally will throw a message in the right pane/git tab that "your branch is ahead of origin"" (i.e., on github) 
#This message means we have changes we can commit to eventually update the file on github.

#Then "pull" using Rstudio radio buttons in the git tab (not on github). "Pulling" is likely to return a "no changes" message if you are the only contributor to the branch.
#Then "push"  using Rstudio radio buttons in the git tab (not on github). "Pushing" sends a request to implement the file changes to github.
#wait for the loading to be over and then click on close. That's it!

#practice: commit-pull-push
