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
```
