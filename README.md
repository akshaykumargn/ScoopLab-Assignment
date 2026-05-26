
# Git Version Control Assignment
## 1. Tracking Local File Changes
Git tracks changes by taking "snapshots" of your project at specific points in time. Instead of saving the entire file every time, Git identifies exactly what lines were added, modified, or deleted. This allows you to revert to previous versions, branch out to try new features, and collaborate without overwriting others' work.

## 2. The Three Git States
To understand how Git works, it is helpful to visualize the three distinct states your files travel through:

Working Directory: Project folder on computer where we actively edit, add, or delete files. It is your "sandbox."

Staging Area (Index): A file (index) that stores information about what will go into your next commit. We "stage" files here to prepare them for a permanent save.

Local Repository (HEAD): Where Git permanently stores the snapshots of our project. Once we "commit" files, they move from the Staging Area into the Local Repository, creating a secure point in history.


# The sequence of Git commands used:
## 1. Initialize the repository
git init

## 2. Set the main branch name
git branch -M main

## 2. Add the remote URL
git remote add origin <repository-url>

## 2. Create the README.md file

## 3. Stage the file
git add README.md

## 4. Make the first commit
git commit -m "Initial commit: Add project README"

## 3. Push the local changes to the remote repository
git push -u origin main
