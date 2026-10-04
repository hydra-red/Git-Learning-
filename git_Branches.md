Git Branches

1. what is a Git Branch?
   A Git branch is a separate line of development in a Git repository. It allows developers to work on different features, bug fixes, or experiments without affecting the main codebase. Each branch can have its own commits and history, making it easier to manage changes and collaborate with others.
2. How to create a Git Branch?
   To create a new branch in Git, you can use the following command:

```
1. ** git branch <branch_name> **: This command creates a new branch with the specified name. For example, `git branch feature-xyz` will create a new branch called "feature-xyz".

2. ** git switch <branch_name> **: This command allows you to switch to the specified branch. For example, `git switch feature-xyz` will switch to the "feature-xyz" branch.

3. ** git checkout <branch_name> **: This command also allows you to switch to the specified branch. For example, `git checkout feature-xyz` will switch to the "feature-xyz" branch. Note that this command is being replaced by `git switch` in newer versions of Git.

4. ** git switch -c <branch_name> **: This command creates a new branch with the specified name and switches to it. It is a shorthand for creating and switching to a new branch in one step.

5. ** git branch -d <branch_name> **: This command deletes the specified branch. For example, `git branch -d feature-xyz` will delete the "feature-xyz" branch. Note that you cannot delete a branch that you are currently on.

6. ** git branch -m <old_branch_name> <new_branch_name> **: This command renames the specified branch. For example, `git branch -m feature-xyz feature-abc` will rename the "feature-xyz" branch to "feature-abc".
```

