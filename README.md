# Git_Version_Control_Assignment

### Version Control
Version control also known as source control or revision control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It involves systematically tracking and managing changes made to software code and files over time. Version control systems are essential tools that assist software teams in overseeing modifications throughout the development process. As developers make edits, the system captures snapshots of the files, preserving them permanently for future reference. This systematic approach enhances team efficiency.

### Git vs GitHub
Git is a distributed version control system, while GitHub is a web-based platform for hosting and collaborating on Git repositories. Git is the tool while GitHub is the service for projects that use Git.

### GitHub Alternatives
1. GitLab
2. Bitbucket
3. Gitea

### Git Fetch vs Git Pull
`git fetch` retrieves changes from the remote repository without merging them into your working branch, while `git pull` fetches and merges changes into your working branch.
`git fetch` also updates your remote-tracking branches, this operation is safe to run at any time since it never changes any of your local branches. while `git pull` brings a local branch up-to-date with its remote version, while also updating your other remote-tracking branches.

### Git Rebase
Git rebase is a command used to integrate changes from one branch into another. It moves or combines a sequence of commits to a new base commit.

Command for Git Rebase:
```bash
git rebase target-branch

## Git Cherry-pick
Git cherry-pick is a command used to apply a specific commit from one branch to another. It allows you to select a commit and apply it onto the current branch.

**Command:**
```bash
git cherry-pick <commit-hash>

where the "commit-hash" is the actual hash of the commit you want to apply.

