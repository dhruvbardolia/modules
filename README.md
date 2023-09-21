# GIT WORKSHOP NOTES
## Git Installation
Windows: https://git-scm.com/download/win

Linux: https://git-scm.com/download/linux

## Repository
A repository contains all of your project's files and each file's revision history. You can discuss and manage your project's work within the repository.

## Branch
Use a branch to isolate development work without affecting other branches in the repository. Each repository has one default branch, and can have multiple other branches. You can merge a branch into another branch using a pull request.

## Staging Area
The Staging Area is when git starts tracking and saving changes that occur in files. These saved changes reflect in the .git directory. That is about it when it comes to the Staging Area. 

## Local Area
The Local Repository is everything in your .git directory. Mainly what you will see in your Local Repository are all of your checkpoints or commits. It is the area that saves everything (so don’t delete it).

## Basis Commands of Git
```git init```

This command Create an empty Git repository or reinitialize an existing one. This command creates an empty Git repository - basically a .git directory with subdirectories for objects, refs/heads, refs/tags, and template files. An initial branch without any commits will be created

```git add```

This command adds a change in the working directory to the staging area. After making changes, running this command will tell git to track this changes. 

```git commit```

This command basically save our tracked changes to the local area. Git add command will only tell git to track the changes, git commit will save the chanegs to the local repository.

```git push```

This commmand will basically save changes to the remote repository. 

```git branch```

This command is used to list, create, or delete the branches from the repository. There are key strokes that can be use. 
- -r will list the branches from remote repository
- -a will list all the branches
- -d to delete a branch