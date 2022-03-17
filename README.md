![git logo](./git.png)


## Table of Contents

- [**Basics**](#Basics)
- [**logging**](#Logging)
- [**Branch**](#Branch)
- [**Miscellaneous**](#Miscellaneous)
## Basics 

#### Initialization
```bash
git init
```

#### Get the status of files
```bash
git status 
```
#### Add to Staging area

```bash
git add . or git add -a 
```
#### Clear the staging area
```bash
git reset
```

#### Commit 
```bash
git commit -m "<msg>"
```

#### Skip staging area 
```bash
git commit -am "<msg>" or git commit -a -m "<msg>"
```

#### What changes have been made?
```bash
git diff <file-name> or git diff 
```

#### Cloning remote repository 
```bash
git clone <link>
```

## Logging 

#### Detailed 
```bash
git log -- or git log -p
```

#### Short 
```bash
git log --oneline
```

#### View last n commits 
```bash
git log -2
```
#### What changes were made in this commit
```bash
git show <commit-id>
```

## Branch

#### Which branch? *
```bash
git branch 
```

#### Create and Switch to new branch 
```bash
git checkout -b <branch name>
```

#### Delete branch (gives error if not merged)
```bash
git branch -d <branch name>
```

#### Delete branch (Deletes even if not merged)
```bash
git branch -D <branch name>
```
#### list the branches with their previous commits 
```bash
git branch -v
```
### which branches are merged?
```bash
git branch --merged 
```

### which branches are not merged?
```bash 
git branch --no-merged 
```
