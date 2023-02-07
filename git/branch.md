# Working with branches

## Create a new branch

`git checkout -b new-branch-name`

The newly created branch is local. To reflect it onto the repository host: 

`git push -u origin newly-created-local-branch-name`

### Examples

#### Create a new `feature/abc` branch

```shell
git checkout -b feature/abc
git push -u origin feature/abc
```

## Switch to a particular branch

`git checkout branch-name`

If you've made some changes in the current branch, you must either commit, stash, or remove them before switching.

### Examples

#### Switch to the `feature/abc` branch

```shell
git checkout feature/abc
```