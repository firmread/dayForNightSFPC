# Day For Night

Hackpad: https://fallsfpc2015.hackpad.com/Day-4-Night-e6Zo9q7mBAs

## Contributing


### Development

It's probably a good idea to work in your own branch. Create a new branch:

```bash
git checkout -b branchName
```


### Submitting Changes

#### If you're adding a new scene and not changing the architecture

Check to make sure you don't have uncommitted changes (commit them if you do):

```bash
git status
```

Now checkout the master branch and make sure it's up to date:

```bash
git checkout master
git pull
```

Now merge in your branch:

```bash
git merge branchName
```

Now push your changes to the repo:

```bash
git push
```


#### If you're making architectural changes

It's probably better to push your branch instead of merging directly into `master`, then submit a pull request.

Check to make sure you don't have uncommitted changes in your branch (commit them if you do):

```bash
git status
```
Now push your branch to GitHub:

```bash
git push origin branchName
```

Now [go to GitHub repo](https://github.com/ofZach/dayForNightSFPC) and submit a pull request via the GH interface.