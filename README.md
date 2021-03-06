# BU CNSO Git Introduction

This repository exists to get people used to git commands and the GitHub
interface.

## Prerequisites

The following steps are required of anybody participating in this introduction.

1. [Sign up for a GitHub account](https://github.com/join)
2. Request to join the [bu-cnso](https://github.com/bu-cnso) group by
   emailing me. (Or the list, if you don't know my email.)
3. [Install](https://help.github.com/articles/set-up-git/) git on your laptop
  1. You can also use a git installation on a server you can SSH into.
  2. The [GitHub client](https://desktop.github.com/) doesn't
     count.
    1. Except that's the way GitHub recommends you to install git on Windows.
       We won't be discussing the graphical client, so make sure you can do
       step 5 from the command-line.
4. [Add a public key](https://help.github.com/categories/ssh/) to your GitHub
   account. The private key should be on the computer you plan to use.
5. Create an initial repository for your user and follow the instructions to
   make an initial commit.

## Lesson plan

Note that lines beginning with `$ ` are shell commands, and the lines following
it are example output. Do not type the `$ ` prompt.

Begin by setting the USER variable to your GitHub username:

```bash
$ export USER=...
```

Or just note that whenever you see `$USER`, you're supposed to put in your
username.

### Some very quick terminology

A *repository* is a directory, its contents, and its history.

A *commit* is a snapshot of the directory contents. A commit usually has one
parent, sometimes two, and rarely zero.

The history of the repository is a collection of commits.

### Topics

* The [GitHub model](github_model.md)
* [Personal projects](personal_project.md)
* [What is git, and what is GitHub?](git_and_github.md)

### The Cheat Sheet

This page will see you through most situations you're likely to run into:
[Git Cheat Sheet](images/cheat_sheet.png)

# About README.md

This file is written in
[Markdown](https://help.github.com/categories/writing-on-github/), a simple
markup language.
