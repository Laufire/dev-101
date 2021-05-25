# git
  
  Common commands.

```sh
# Initialize a repo.
$ git init

# Add a remote URL to the repo ($ github URL)
$ git remote add origin <URL>

# List remotes
$ git remote -v

# List all possible files ready for staging.
$ git add . --dry-run

# Stage all possible files.
$ git add .

# Commit
$ git commit -m "<message>"

# Push for the first time.
$ git push --set-upstream origin master

# Push for after the first time.
$ git push

# List all commits.
$ git log

# Pull remote changes.
$ git pull

# Move / Rename a file.
$ git mv <src-file-path> <dest-file-path>

# Sync with master
$ git fetch --all

# Push Tags
$ git push --tags
```
