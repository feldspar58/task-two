# This is task two for learnable intership

My name is joseph Anyigor and this is my task for week two

## Table of content
- Explain version control
- Explain difference between git and github
- List 3 other github alternatives
- Explain the difference between git fetch and git pull
- Explain in simple terms git rebase and the command for it
- Explain in simple terms git cherry-pick and the command for it

### Explain version control


Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It is commonly used in software development to manage changes to source code, but it can be applied to any kind of file. The primary purpose of version control is to enable collaboration among multiple contributors while providing a history of changes and the ability to revert to a specific version if needed.Git is one of the most widely used distributed version control systems. It was created by Linus Torvalds and is open source.

### Explain difference between git and github

Git is a distributed version control system (DVCS) that allows developers to track changes in their codebase, collaborate with others, and manage different versions of their projects.
GitHub is a web-based platform that provides hosting for Git repositories and offers additional collaboration and project management features.
Git provides core version control functionalities like committing changes, branching, merging, and history tracking.
It operates locally on your machine, allowing you to work offline and commit changes to your local repository.
GitHub extends the functionality of Git by providing features like pull requests, issues, code reviews, and project management tools.
It allows teams to collaborate more effectively, track issues, and manage project workflows.
Developers use Git for version control in their local development environments.
It is a command-line tool, but there are also various graphical user interfaces (GUIs) available.
GitHub is an online service that hosts Git repositories. Developers and teams can use it to store, share, and collaborate on their Git repositories.
It provides a web interface for managing repositories and interacting with Git features.
Git repositories can be hosted on any server or used locally without any remote server.
GitHub hosts Git repositories in the cloud, making it easy for teams to collaborate and contribute to open-source projects.
It provides a centralized platform for collaboration, allowing multiple developers to work on the same project and contribute changes.

### List 3 other github alternatives

- Gitlab
- Bitbucket
- GitKraken

### Explain the difference between git fetch and git pull

git fetch is primarily used to download new changes from the remote repository to your local repository. It updates the remote-tracking branches but does not automatically merge the changes into your working directory. 
When you run git fetch origin, Git contacts the remote repository (in this case, "origin") and fetches any new branches or changes made by others. However, your local working directory remains unchanged. 
Use git fetch when you want to see what changes are available on the remote repository but do not want to automatically merge them into your current working branch.

git pull is a combination of git fetch and git merge. It not only downloads the changes from the remote repository but also automatically merges them into your current working branch. 
When you run git pull origin master, Git will fetch the changes from the remote master branch and automatically merge them into your local master branch.
Use git pull when you want to fetch the changes from the remote repository and also merge them into your current working branch. 

### Explain in simple terms git rebase and the command for it

git rebase is a Git command that helps you reorganize or clean up your commit history by moving or combining commits. It's like rewriting the history of your changes.
Git will find the common ancestor commit between your branch and the branch you are rebasing onto.
It then applies your changes on top of the other branch, making it look like your changes were added directly on top of the latest commit in the other branch.
The commit history becomes more linear, and your changes are integrated smoothly.
If you have multiple small, intermediate commits, you can rebase them into a single commit or a cleaner sequence. Never rebase commits that you've already pushed to a shared repository.
The command to initiate a rebase is 'git rebase'.

### Explain in simple terms git cherry-pick and the command for it

git cherry-pick is a Git command that allows you to pick and apply specific commits from one branch to another. It's like selecting individual changes and bringing them into your current branch. Git takes the changes introduced by the specified commit and applies them as a new commit on your current branch.
The specific changes from the cherry-picked commit are now included in your current branch.
The command to cherry-pick a commit is git 'cherry-pick'
