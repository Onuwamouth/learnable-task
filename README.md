# learnable-task
1 Explain version control.

* Version control is the practice of tracking and managing changes to software code. Version control systems are Software tools that help software teams manage changes to source code over time.


2 Explain the difference between git and github.

* Git is the most popular VCS in use today, created by Linus Torvalds in 2005. It is free, open-source, and designed to handle everything from small to very large projects with speed and efficiency. Its flexible architecture means it can be effectively integrated into your workflow.

* Git hub is a web-based hosting service for Git repositories. It makes Git more user-friendly and also provides a platform for developers to share code with others. In addition, GitHub makes it easy for others to contribute to projects. It also has a robust API that allows developers to integrate GitHub into their own applications and workflows.

* GitHub offers both a paid and free subscription. With a free subscription, users can create public repositories. Public repositories are visible to anyone and can be cloned or forked by anyone. (A fork is a separate copy of the Git repository that was made. A clone, in contrast, creates a linked copy that will continue to synchronize with the target repository.) A paid subscription is required to create private repositories. Private repositories are only visible to users who have been given access by the repository owner.

* GitHub is built on Git.

3 List 3 other github alternatives

* Bitbucket
* Gogs
* Jira

4 Explain the difference between git fetch and git pull,

* The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.
git fetch command fetches all the changes from the remote repository to the local repository without bringing the changes into the working directory. Git Pull on the other hand brings the copy of the remote directory changes into the working directory.

5 Explain in simple terms git rebase and the command for it

* Rebase is one of two Git utilities designed to integrate changes from one branch onto another. Rebasing is the process of combining or moving a sequence of commits on top of a new base commit. Git rebase is the linear process of merging.

* git rebase command for launching a standard rebase is `git rebase <base>`.

* git rebase command for launching an interactive rebase is `git rebase --interactive <base>`.

6 Explain in simple terms git cherry-pick and the command for it

* git cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another. git cherry-pick can be useful for undoing changes. For example, say a commit is accidently made to the wrong branch. You can switch to the correct branch and cherry-pick the commit to where it should belong.

To cherry-pick in git, Follow the steps below:

* Find the commit ID by running `git log`

* Switch to the branch you want to cherry-pick the commit to by running `git switch <branch name>`

* cherry-pick the commit using the commit ID you copied from the log by running `git cherry-pick <commit id>`

* run the command `git reflog` to check if the git cherry-pick was successful.