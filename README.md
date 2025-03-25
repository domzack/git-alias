# git-alias
automatic commit and push

setup:
$ git config --global alias.pop '! pop() { git commit -a -m "$1" && git push && git status ; } ; pop'

usage:
$ git pop "my commit message"

Git Cli install: https://github.com/cli/cli#installation
