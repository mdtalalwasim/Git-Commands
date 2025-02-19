# Git-Commands
Git Commands are listed here


#### To cherry-pick a commit
```bash
git cherry-pick #commit_hash
```



#### To delete a local branch from a Git repository using the terminal
```bash
git branch -d branch_name;
```



#### To cherry-pick a specific commit in Git
##### To cherry-pick a specific commit in Git
Just go to the target branch first then,
```bash
git checkout <target-branch>
git cherry-pick dfa266d //here 'dfa266d' is commit hash. 
```

#### Reset to the Last Commit
##### If you want to discard changes that are not yet committed:
```bash
git reset --hard HEAD

```

#### Merge Command
##### If you want to Merge "dev" branch with "Main" branch:
```bash
git checkout main   [Note: First switch to Main branch]

git merge dev_branch 
```

#### Check Current Branch
```bash
git branch
```


#### Check Git Current status
```bash
git status
```
#### Check log
```bash
git log
```

#### Switch to specific Branch
```bash
git checkout put_branch_name_here
```

#### Create new Branch
```bash
git checkout -b put_new_branch_name_here
```
#### Upload all files on the stage for certain folder
```bash
git add .
```
#### Upload specific files(wasim.txt) on the stage
```bash
git add wasim.txt
```

#### To force Git to add the ignored file (application.properties), you can use the -f flag with the git add command, as suggested in the hint: 
```bash
git add -f application.properties
```



