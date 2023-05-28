# my git_test repository
>This Repo is from TOP's GIT basics, and contains only the commands needed to complete the lesson, without duplicates.

>The Git commands I'm following in order, keeping note of them for future reference. Specifically using SSH (Not HTTPS).
<!-- GIT notes -->
#
## git clone
>this @ comes directly from the green code button on each repo's page.

    git clone git@github.com:USER-NAME/REPO-NAME.git

#
## git remote 
>displays URL of current working repository.

    git remote -v

#
## git status
>shows the current status of your working git tree and shows which files need to be staged, committed, or nothing if all is up to date.

    git status

#
## git add
>adds the specified file to the working tree staging area.

    git add file_name.extension

#
## git commit
>pushes the staged changes to main, with -m "txt" being the note or message for the commit that is displayed.

    git commit -m "Put commit message here"

#
## git log
>will show the history of changes made to the repo as well as the author of said changes, all timestamped.

    git log

#
## GIT cheatsheet

>This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:

Commands related to a remote repository:
*     git clone git@github.com:USER-NAME/REPOSITORY-NAME.git

*     git push

or
*     git push origin main

>(Both accomplish the same goal in this context)

Commands related to the workflow:

*     git add .

*     git commit -m "A message describing what you have done to make this snapshot different"

Commands related to checking status or log history

*     git status

*     git log
The basic Git syntax is
>program | action | destination.

For example,

*     git add . 

is read as 

>git | add | .

where the period represents everything in the current directory;

*     git commit -m "message" is read as git | commit -m | "message"

and
*     git status

is read as
>git | status | (no destination).