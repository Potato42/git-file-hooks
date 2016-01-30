# git-file-hooks
git hooks for editing and creating files

These are really simple and mostly just here as an experiment with git hooks, but they do solve a minor annoyance I've had with git.

## Installation
Just dump `git-create` and `git-edit` into a folder in your path.

## Usage

```shell
# create (touch) a file named potato, adding it to git
git create potato

# edit the file potato with $EDITOR.  After $EDITOR finishes, add it to git
git edit potato

# git-edit the file potato with Sublime Text instead of $EDITOR.  Note that we
# use subl's -w argument to wait for it to finish before continuing.  You
# might consider making an alias if you want to do this often.
git edit potato "subl -w"
```
