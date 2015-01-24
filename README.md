# git-open
A command-line script to open the GitHub page for a repository.

## Usage
    git open [remote-name] [branch-name]

### Examples
    $ git open
    > open https://github.com/REMOTE_ORIGIN_USER/CURRENT_REPO/tree/CURRENT_BRANCH

    $ git open upstream
    > open https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/CURRENT_BRANCH

    $ git open upstream master
    > open https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/master


## Installation

Put the bash script in `~/bin/` and make sure that folder's in your PATH.

```sh
wget -O ~/bin/git-open https://raw.githubusercontent.com/paulirish/git-open/master/git-open
```

