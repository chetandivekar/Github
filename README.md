
## Author

- [@chetandivekar](https://github.com/chetandivekar)



## SETUP
Configuring user information used across all local repositories.


set a name that is identifiable for credit when review version history

```bash
    git config --global user.name “[firstname lastname]”
```

set an email address that will be associated with each history 
```bash
    git config --global user.email “[valid-email]”
```

## INIT
Configuring user information, initializing and cloning repositories.

initialize an existing directory as a Git repository
```bash
    git init
```
retrieve an entire repository from a hosted location via URL
```bash
    git clone [url]
```


## The Git Cheat Sheet for Beginners 

Steps:

Step 1: First add the files in Git using the following command :

```bash
    git add [file-name] 
```
To add All the file at once use following command :

```bash
    git add .
```

Step 2: After adding files we have to commit those file. Basically commits are the snapshots or milestones and takes your files into the stagging arear. For commit the file use following command :

```bash
    git commit -m "[Write-Message]"
```

To unstage the file use the following command:

```bash
    git reset [file-name]
```

To Delete/Clear the stagging area use the following command:

```bash
    git reset --hard [file-name]
```

You can check the status of your files by following command:

(Status give the info about the files, like which files are added, modified, deleted and give info about branches.)

```bash
    git status
```

To check the logs use the following command:

```bash
    git log
```


## Branch

To list all the branches use following command:

```bash
    git branch 
```
To create a new branch use following command:

```bash
    git branch [branch-name]
```

To go into that branch use following command:

```bash
    git checkout [branch-name]
```


## Push
add a git URL a

```bash
    git remote add origin ['your_url_name']
```

Transmit local branch commits to the remote repository branch using following command

```bash
    git push [branch-name]
```


#

![Logo](https://i.kym-cdn.com/photos/images/original/001/704/393/8d2.png)

