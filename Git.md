# Git

## Ignoring directories in Git repos

[Ignoring directories in Git repos on Windows](http://stackoverflow.com/questions/343646/ignoring-directories-in-git-repos-on-windows)

Create a file named .gitignore in your projects directory. Ignore directories by entering the directory name into the file (with a slash appended):

```.gitignore
dir_to_ignore/
```

note: files tracked before can be untracked by running

```shell
git rm --cached filename
```