# git-squash
Custom command for git to squash the most recent n commits into the previous.
Will show the commit messages of the commits to be squashed, and ask for confirmation before proceeding.

## Installation

Place the file `git-squash` in `/usr/local/git/bin` and make it executable.
Git will find it, and make it behave like any other git command.

## Usage:
```
git squash 2
```
Will squash the 2 most recent commits into the previous commit.
