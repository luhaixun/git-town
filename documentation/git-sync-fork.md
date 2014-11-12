#### NAME

git-sync-fork - synchronize a forked repository

#### SYNOPSIS

```
git sync-fork
git sync-fork --abort
```

#### DESCRIPTION

Pulls updates from the upstream main branch into the main branch of this repository.
If your repository is on GitHub, the git remote `upstream` will be automatically set on first use.

#### Options

```
--abort
  Cancel the operation and reset the workspace to a consistent state.
```