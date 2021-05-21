### Git Commands  # ``` -uptakes

```
git init
```
This command initialize git.

```
git add
```
This command adds the file to staging area.

```
git commit
```
This command records the file in the version history. 

```
git diff
```
This command shows the differences which are not staged yet.

```
git diff --staged
```
This command shows the differences between staging area and the latest version.

```
git reset
```
This command unstages the file.

```
git status
```
This command lists all the files that have to be tracked and/or commited. 

```
git rm filename
```
This command will delete the file and the staging area will know about deletion of the file. (when we use "git add command- usually it pushes files to the staging area)

```
rm -f filename
```
This command will delete the file, but it will not be updated on the staging area, staging area will not be aware of the file deletion. In this scenario we need to do several steps to let the staging area know about changes that were made.  (Nothing can be commited, until they are staged)

```
git log
```
This command show if commit was made.

```
git show commitid
```
This command will show you details of the commit.

```
git revert
```
Git revert is dangerous, couse it is going to delete. This command will revert back file from the commit.

```
git branch branch/name
```
This command will create a new branch with branch/name. You can choose any name that you want. 

```
git checkout -b branch/name
```
This command will create a new branch with branch/name and switch to it. It is a combination of two commands "git branch branch/name and git checkout branch/name"

```
git checkout branch/name
```
This command will switch branch to branch/name branch. 

```
git branch -d branch/name 
```
This command will delete brach called branch/name. 


#### Questions

What is GitHub?
```
- VSC(Version Control System) and SCM(Source Code Management)
- source code management. 
- remote location for our code. (location to store our codes(files))
- it has built in git.
```

What is Git?
```
- git is the tool which support version control system. 
Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems)