# Astronomy 100 (Spring 2020)
This is the best class ever!!!!   (says Doug)
Class will be held Tuesday and Thursday in the Science Center Room 804 (FAS) from 3.00pm to 4.45pm. Notes and materials will be posted to this repository. Office hours will take place after class.


## Setting up Github

The following will add my repository as `upstream` to your remote access points, which means you can pull all the changes and homework that I add to my repository.

`git remote add upstream https://github.com/lockepatton/ASTR100-2020`

See all the remotes you have:

`git remote -v`

`origin` is your forked repository

`upstream` is the original repository, which you just added to your list of remotes.


## How to update your repository with the changes in mine (!! do this each time)

This will give you homework assignments and my notes from class, on your forked repository.

`git pull upstream master`


## GitHub 101

### How to add your homework to your repository:

Make git track all the files you'd like to add to your repository by running the command below for each file.

`git add FILE(S) YOU WANT TO ADD`

Check which files are tracked, and if more changes have been made to each with:

`git status`

When you're happy with everything you've added (and the version they were in when you added them), run a commit statement. This is like a checkpoint.

`git commit -m "LEAVE A NOTE TO YOUR FUTURE SELF ABOUT WHY YOU'RE SAVING YOUR WORK HERE"`

When you'd like all of the changes you've committed to be on your repository online (where everyone can access them), run the following:

`git push`

Check your github repository online and see your changes.

### Pull Request - the final step for handing in homework.

Once you've committed and pushed your changes to your forked repository, go to your repo online and click on 'Pull Request'. Go through the process of creating a pull request and add any notes about the changes you've made. Preferably include notes about which HW you've added!

## Some notes Locke once made about unix - use at your own risk :)

https://github.com/lockepatton/code-notes
