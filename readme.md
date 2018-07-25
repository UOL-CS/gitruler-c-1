<!--
Marked Style: Github
-->

# GitRuler Section C

This repository is section C of the [GitRuler exercises](https://github.com/UOL-CS/gitruler-exercises).

In this exercise we will learn about moving and removing files within a repository and telling git to ignore a set of files.

## Introduction

If you do not already have a your own repository for these exercises [fork this repository](https://help.github.com/articles/fork-a-repo/). Clone this repository

At any time you can run gitruler to check your progress. From the command line run:

`java -jar <path to gitruler.jar>`

For more information on running gitruler look at the [project repository](https://github.com/rcraggs/gitruler).

## Instructions

1. After cloning the repository change into the director on a [command line](https://www.techopedia.com/definition/3337/command-line-interface-cli).
2. Run gitruler to initialise the exercise.

## Ignoring Files

If there are many files in our directories that we never want to track using git then we can tell git to ignore them. This often happens when programming where we don't want to commit compiled files. 

Imagine that the editor that our shop-keeper uses creates backup files whenever he edits a file. The `files/ideas` folder is full of `.bak` files. Rather than having to keep deleting these and so that we can add the whole `ideas` directory to a commit without adding these files, we want to ignore all them.

There is also a `files/ideas/drafts` folder where he keeps files that are not yet ready to commit. We want git to always ignore files within this folder.

1. Create the necessary file and contents so that git will ignore all files ending with `.bak` in the `files/ideas` folder and everything in the `files/ideas/drafts` folder.
2. Commit this file with the commit message "Ignore draft and backup ideas".
3. Commit all of the `.txt` files in the `files/ideas/` folder (you should now be able to stage them all with a single `git add` command) with the commit messages "Add extra ideas".




## Resources

1. There are many resources about how to tell git to ignore files or folders. One example is in the [Atlassian git tutorial](https://www.atlassian.com/git/tutorials/saving-changes/gitignore)






