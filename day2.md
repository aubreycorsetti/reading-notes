# Day 2

## All about Git, GitHub and Repositories

### What is GitHub?

> GitHub is a website that uses Git to do a few things such as

* Share your code with others
* Online backup system, a cloud of data storage
* Uses Git to track your work

### What is Git?

> Git is an open source software for distributed version control. Otherwise known as DVCS.

Git can reside in 3 main stages.

* Commited: Data is securely stored in local database

* Modified: File has been changed but not commited to the database

* Staged: Flagged a file's changed version to be commited into the next snapshot

### What is a Repository?

> A repository is a folder or file being tracked with Git.

* Usually one project= one repository
* Really large projects might have multiple repositories for different parts of a project
* Repositories can live on GitHub and/or your computer

### Cloning/Merging Repositories from VS Code to GitHub

> Retrieve your GitHub clone link and head to your terminal to type in these instructions always followed by the enter key.

1. git clone putyourlinkhere
2. git status
3. git add .    -Putting the dot will add everything
     to add only specified files you can do the following
     * git add filenamehere
     *you can add as many files as you want but be sure to add a space between the file names*
4. git commit -m ""     -Insert a message between the quotation marks explaing why you changed the file
5. git status
6. git push origin main     -This pushes the new information back into GitHub

[Click here to return Home](README.md)
