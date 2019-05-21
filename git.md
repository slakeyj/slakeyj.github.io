## What is Version Control? 

Version Control allows you to revisit different versions of a file by recording those changes.  

Types of Version Control:

- Local Version Control: One database on your hard drive that stores changes to files.

- Centralized Version Control System (CVCS): A single server storing all changes and versions of files which can then be accessed by different clients. 

- Distributed Version Control System (DVCS):  Allows clients to create mirrored repositories.  This helped to eliminate the weakness of a CVCS's one centralized point.

## What is Git? 

- Git is a distributed version control system (DVCS) that stores data in a file system made up of snapshots.
- Each time you make a commit (save a project) git creates a reference to that commit.
- Files in git reside in 3 main states:
  - Committed: Data securely stored in a local database.
  - Modified: file has been changed, but not committed;
  - Staged: A changed version of a file that is flagged to be committed.
  
#### The local respository has 3 components: 
1. Working Directory:  Where actual files reside.
2. Index: Area used for staging.
3. Head: Points to the most recent commit.

#### The Life Cycle of File Status 
- After you edit a file, git flags it as having been modified.
- You then stage the modified file.
- Then you commit the staged changes.

## Git Commands

#### Check Status 
```$ git status```

Determines the state of the files.

#### Staging
```$ git add (filename)```

or

``` $ git add *```

This will track all files in a repository.

#### Commit
```$ git commit -m "Comments on what changes were made"```

or

```$ git commit -a```

Commits all modifications of tracked files in a working directory.

#### Push

```$ git push origin masster```

Pushes changes from local master branch to remote repository name "origin".

#### Remote Repositories

Versions of a project residing online or on a network.

```$ git remote```

Gives a view of the short names of all remote handles.

```$ git remote -v```

Lets you view all remote URLs next to their short names.



