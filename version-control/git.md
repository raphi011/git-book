# Git

## Useful commands I always forget:

### Finding lost changes

Search the rev-list for changes in a file:

```
git rev-list --all -- relative/path/to/file.go
```

Search the reflog for commit messages:

```
git reflog --grep-reflog=regex
```
