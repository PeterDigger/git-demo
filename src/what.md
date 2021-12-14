# Basics of Git

## Stages

Stages are the terms for everyone to call before add commit log in remote repository.

- Untracked: the file exists, but is not part of git's version control
- Staged: the file has been added to git's version control but changes have not been committed
- Committed: the change has been committed

Read More: [http://archaeogeek.github.io/foss4gukdontbeafraid/git/stages.html](http://archaeogeek.github.io/foss4gukdontbeafraid/git/stages.html)

## Branches

Git branches are effectively a pointer to a snapshot of your changes. New commits are recorded in the current branch's history, resulting in a fork in the project's history. They can be thought of as a mechanism to request a whole new working directory, staging area, and project history.

![branch](https://wac-cdn.atlassian.com/dam/jcr:a905ddfd-973a-452a-a4ae-f1dd65430027/01%20Git%20branch.svg?cdnVersion=130)

More: [https://www.atlassian.com/git/tutorials/using-branches](https://www.atlassian.com/git/tutorials/using-branches)

## Commit

The git commit command is one of the core primary functions of Git. The git commit and git add commands are used to select the changes that will be staged for the next commit. Then git commit creates a snapshot of the staged changes along a timeline of a Git projects history.

More: [https://www.atlassian.com/git/tutorials/saving-changes/git-commit](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)

## Merge

Merge is for the combining sequences of commits into one unified history of commits.
Git can automatically merge commits unless there are changes that conflict in both commit sequences.

More: [What is merge Conflict?](../done/conflict.md), [Git merge by Atlassian](https://www.atlassian.com/git/tutorials/using-branches/git-merge)

# Github

>GitHub, Inc. is a provider of Internet hosting for software development and version control using Git. It offers the distributed version control and source code management functionality of Git, plus its own features[^1]

These are features mentioned is what Git fall short. And there are many more features and details that will be not mentioned due to author is having exam coming soon.

## Fork

A fork is a copy of a source code version of a repository, which means you can make changes to the source code without affecting the original project's source code.

## Pull request

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss potential changes with collaborators and add follow-up commits.

---

Want to learn more?

- [https://www.atlassian.com/git/tutorials/what-is-version-control](https://www.atlassian.com/git/tutorials/what-is-version-control)

[^1]:https://en.wikipedia.org/wiki/GitHub
