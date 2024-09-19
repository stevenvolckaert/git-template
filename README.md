# git-template

A default directory structure for projects that use Git.

## Getting started

Initialize a new Git repo containing the contents of **git-template** without its history:

``` bash
~$ mkdir new-project
~$ cd new-project
~/new-project$ git archive --remote=https://github.com/stevenvolckaert/git-template.git HEAD | tar -x
~/new-project$ git init
~/new-project$ git add --all
~/new-project$ git commit -m "Initial commit"
```
