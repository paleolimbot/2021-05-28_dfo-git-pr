
# 2021-04-30 R Learning and Development Git/GitHub practice

Today's exercise is a collection of common actions for using Git and GitHub from RStudio. The actions we will practice are:

- **Fork** a repository (make a copy of somebody else's repository on your own account). To do this you will need to [create a GitHub account](https://github.com/join) if you haven't already.
- **Clone** a repository (make a local copy of a GitHub repository on your computer so you can edit the files). Do to this you will need to [install Git](https://happygitwithr.com/install-git.html#install-git-windows) if you haven't already and make sure RStudio knows that Git exists on your system.
- **Commit** a change to one or more files in the repository.
- **Push** your changes back to GitHub. This includes [setting up RStudio to talk to GitHub](https://happygitwithr.com/credential-caching.html#how-to-get-a-pat) if you haven't already!
- **Pull Request** your changes back into this repository!


## Fork

In order to practice using Git/GitHub, you will need a repository to work from! To get started, click the "Fork" button at the top of this page. To do this you will need to [create a GitHub account](https://github.com/join) if you haven't already (you'll be prompted to create one or sign in when you click "fork").

![](screenshot/fork.png)

## Clone

Once you have your own repository, (i.e., the address of the repository should be https://github.com/YOUR_USER_NAME/2021-04-30_dfo-git), you will need to **clone** the repository to your own computer to make changes in RStudio. From RStudio, click on *New Project* at the top right hand of the window. You should see a screen that looks like this:

![](screenshot/clone-rstudio.png)

If you don't see *Version Control* as a third option, you probably haven't installed Git. There are excellent instructions for installing git in [Chapter 4 of Happy Git With R by Jenny Bryan](https://happygitwithr.com/install-git.html#install-git-windows). You'll have to restart RStudio after installing Git and you should see the *Version Control* option. Click on *Version Control* and you should see a screen that looks like this:

![](screenshot/clone-rstudio-2.png)

Click on *Git* and you should see a screen that looks like this:

![](screenshot/clone-rstudio-3.png)

The *Repository URL* you need is located on your GitHub repository page under the green *Code* button. Unless you know what SSH is and have it set up on your computer already, **make sure you have *HTTPS* selected**. Click the little clipboard icon to copy the value to your clipboard.

![](screenshot/clone.png)

Paste the value under *Repository URL* and click *Create Project*.

## Commit

Open *participants.md* and follow the instructions at the top of the page. Click on the *Git* tab at the top right of the RStudio window. You should see a window that looks like this:

![](screenshot/commit.png)

Check the boxes next to all the files and click *Commit*. You should have a window pop up that gives you an opportunity to add a small message. Type something in the box and click *Commit*.

![](screenshot/commit-2.png)

## Push

After you have committed your change, push it back to GitHub using the green arrow in the *Git* pane. If your computer has already been set up to work with GitHub, you shuld see the following window:

![](screenshot/push.png)

If not, you'll see some kind of error message and you will need to set this up. There are excellent instructions on how to do this in [Chapter 10 of Happy Git With R by Jenny Bryan](https://happygitwithr.com/credential-caching.html#how-to-get-a-pat) but don't be afraid to ask for help getting this to work!

Visit your repository page on GitHub (https://github.com/YOUR_USER_NAME/2021-05-28_dfo-git-pr) and click on *participants.md*. Your changes should be there!

## Pull Request

The final step is to "pull" the changes back into this repository! To do this, visit your repository page on GitHub (https://github.com/YOUR_USER_NAME/2021-05-28_dfo-git-pr) and click on "contribute", then "Open Pull Request".

![](screenshot/pull-request.png)
