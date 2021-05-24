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
git branch -d branch/name(local-branch-name) 
```
This command will delete brach called branch/name. Note: In some cases, Git might refuse to delete your local branch: when it contains commits that haven't been merged into any other local branches or pushed to a remote repository. This is a very sensible rule that protects you from inadvertently losing commit data.

```
git branch -D <local-branch-name>
```
This will force deletion of the branch, even if it contains unmerged / unpushed commits. It goes without saying: please be careful with this command.

```
git push origin --delete <remote-branch-name>
```
To delete a remote branch.

```
git fetch
```
This command will check if there is any difference between your cloned repository/local repository and remote repository. fetch will not copy anything, it will just fo and check the remote and that's it. Read about git pull..

```
git pull
```
This command will go and check your remote repository for changes and will copy changes to your local repository. See the difference between fetch and pull. https://www.freecodecamp.org/news/git-fetch-vs-pull/#:~:text=git%20fetch%20is%20the%20command,changes%20from%20the%20remote%20repository. (well explained link for fetch and pull)



!!!commands to learn
```
git blame
git fetch and git pull prractice
```

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

How to add your(machine's) ssh key to GitLab? See below link, everything is explained step by step. 
```
https://docs.gitlab.com/ee/ssh/
```

How to import your GitHub repository to GitLab? See below links.
```
https://docs.gitlab.com/ee/user/project/import/github.html#use-cases
https://stackoverflow.com/questions/54972004/move-a-repository-from-github-to-gitlab#:~:text=Import%20will%20take%20a%20couple,wiki%2C%20issues%20and%20merge%20requests.
```

Difference between git fetch and git pull?
```
https://www.freecodecamp.org/news/git-fetch-vs-pull/#:~:text=git%20fetch%20is%20the%20command,changes%20from%20the%20remote%20repository.
```

How do I delete a local/remote branch in Git?
```
https://www.git-tower.com/learn/git/faq/delete-local-branch/
```

What does git pull origin master do?
```
https://www.git-tower.com/learn/git/faq/git-pull-origin-master/
```

What is git push?
```
https://www.git-tower.com/learn/git/commands/git-push/#:~:text=In%20case%20you%20are%20using,Push%22%20button%20in%20the%20toolbar.
```
How to Push Local Git Repo to Remote Repo in GitHub?
```
https://jdhao.github.io/2018/05/16/git-push-local-to-remote/
```