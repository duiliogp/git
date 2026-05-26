### Git Quick Reference 

```bash
# Stash
git stash
git stash pop
git stash save "DESCRIPTION"
git stash push -m "DESCRIPTION" path/to/file.txt


# Sets a global file to ignore files across all Git repositories.
git config --global core.excludesfile ~/.gitignore_global
# Create the global gitignore file
touch ~/.gitignore_global # UNIX
New-Item -Path ~\.gitignore_global -ItemType File #POWERSHELL

# Skip Worktree 
git update-index --skip-worktree path/to/file.txt
git update-index --no-skip-worktree path/to/file.txt
```



