# Local Git Command Notes

These are commands I am learning while working with Git locally from PowerShell.

## Repository Information

### Check Git status

```powershell
git status
```

Shows the current branch and the state of files in the working directory and staging area.

### View configured remotes

```powershell
git remote -v
```

Shows the remote repositories associated with the local repository.

### View branches

```powershell
git branch
```

Shows the local Git branches. The active branch is marked with an asterisk.

### Create and switch to a new branch

```powershell
git switch -c feature/branch-name
```

Creates a new branch and immediately switches to it.

## Basic Workflow

```text
Edit files
   ↓
git add
   ↓
git commit
   ↓
git push
```