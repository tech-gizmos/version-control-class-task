## what is version control?

Imagine you're working on a project with others, and each of you is making changes to the project's files. Without version control, it can get chaotic – you might overwrite each other's work, and it's hard to keep track of who did what.
Version control, like Git, steps in to solve these problems. It keeps a detailed history of all changes made to files. Each change is called a "commit," and it includes information about what was modified and why. This allows you to roll back to a previous version if something goes wrong.
Git also enables collaboration by letting multiple people work on the same project simultaneously. Each person can create their own "branch" to work on a specific feature or bug fix independently. Once the work is done, these branches can be merged back together.
In a nutshell, version control systems make collaboration smoother, provide a safety net in case of mistakes, and help maintain a clear record of project changes over time.

## Difference between git and github?

Git is the version control system you install and use locally on your machine, while GitHub is a web-based platform that provides a centralized location for hosting Git repositories and adds collaboration features on top of Git. You can use Git without GitHub, but GitHub makes it easier to collaborate with others and provides a central place to host your Git repositories.

## List three other github alternatives

- [sourceforge]
- [gitlab]
- [gitkraken]

## Difference between git fetch and git pull

- [git fetch:
Fetches changes from a remote repository to your local repository.
It doesn't automatically update your working files.
Useful for checking what changes exist before deciding to merge.]

- [git pull:

Fetches changes from a remote repository to your local repository AND automatically updates your working files.
It's like doing git fetch followed by git merge in one command.
Quick way to get the latest changes and update your working files.]

## Git rebase and the command for it

git rebase is a command that allows you to move or combine a sequence of commits to a new base commit. This essentially rewrites the commit history, making it appear as if the changes were made on top of the latest commit.

The command for git rebase is "git rebase <base>". where "base" is the commit reference (like a commit hash or a branch name) that specifies where you want to place your changes.

## Git cherry-pick and the command for it

git cherry-pick is a command used to apply a specific commit from one branch to another. It allows you to pick and choose individual commits and apply them to a different branch.

The command for git cherry-pick "git cherry-pick <commit-hash>". "commit hash" is the hash of the commit you want to apply.

