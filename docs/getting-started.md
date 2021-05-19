---
title: Getting started
---

## Installing

Let's install Git.

### Platforms

#### Windows
Download the latest [Git SCM installer](https://git-for-windows.github.io) and follow the instructions.

#### Mac
Download the latest [Git for Mac installer](https://sourceforge.net/projects/git-osx-installer/files/) and follow the instructions.


### Checking your installation
To open a command line, if you're on a **Mac,** open up the **Terminal** application, and if you're on **Windows**, open up the **Command Prompt** application.  
  
Type in the following text and press `ENTER`:
```
git --version
```
If installed correctly, Git will print out the installed version:
```bash
jacksonrakena@Jacksons-MacBook-Air ~ % git --version
git version 2.30.1 (Apple Git-130)
```
That means Git is installed, version **2.30.1** on the **Apple Git 130** release.

If you type `git help`, Git will print out all available commands:
```
jacksonrakena@Jacksons-MacBook-Air ~ % git help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
```

## Setup
Now we need to create a "repository" (repo), which is like a workspace for our project.
Create a new folder and change into it:
```
mkdir my-repo
cd my-repo
```
And tell Git to initialize a repo:
```
git init
```
And Git will tell us that it's done our bidding:
```
Initialized empty Git repository 
in /Users/jacksonrakena/Downloads/my-repo/.git/
```