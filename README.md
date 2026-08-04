# Step-by-step instructions for new repository

### Create new account on GitHub if you don’t have one.

### Register a new remote repository called  `new-project`.

### Create a directory `new-project` locally and switch to it:

```bash
mkdir new-project
cd new-project
```
### Initialize git in this directory with command 
```bash
git init
```
### Link local git repository to a remote repository on GitHub like this

```bash
git remote add origin https://github.com/vldmrhlushko/new-project.git
```

### create new branch with name "development" and switch to it

```bash
git checkout -b development
```

### Work on new features in this directory and add files for commiting

```bash
git add README.md 
```

### Commit changes to local git repository with a message

```bash
git commit -m "PROM-42164 #comment Instruction prepared"
```

###  Merge changes from the "development" branch into the "main" branch

```bash
git checkout main
git merge development
```

### Push both branches to remote git repository

```bash
git push --all
```








