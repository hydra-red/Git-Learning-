Stashing

1. ** git stash **: Temporarily shelves (or stashes) changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on. Use `git stash save "message"` to save your changes with a message. 
2. ** git stash save <message> **: Saves your local modifications to a new stash with an optional message describing the changes.

3. **git stash list **: Lists all the stashes you have saved. Each stash is identified by a unique name, such as `stash@{0}`, `stash@{1}`, etc.
4. ** git stash apply **: Applies the changes from the most recent stash to your working directory. Use `git stash apply stash@{n}` to apply a specific stash.

5. ** git stash pop **: Applies the changes from the most recent stash and removes it from the stash list. Use `git stash pop stash@{n}` to pop a specific stash.

6. ** git stash drop **: Removes a specific stash from the stash list. Use `git stash drop stash@{n}` to drop a specific stash.

7. ** git stash clear **: Removes all stashes from the stash list, effectively clearing your stash history. Use this command with caution, as it permanently deletes all stashed changes.