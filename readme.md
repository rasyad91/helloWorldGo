# GoSchool Git tutorial

### Git tutorial <br />

Add file to staging
```bash
git add <file>
```

Add 2 files to staging
```bash
git add <file1> <file2>
```

Add all files in current folder to staging
```bash
git add .
```

Restores file/s => provided not added
```bash
git restore <file> ...
```
 
Removes file from staging, back to working stage
```bash
git restore --staged <file> ...
```

Commits with message
```bash
git commit -m "insert message"
```

Shows existing branches 
```bash
git branch
```
 
Creates new branch
```bash
git branch "branch name"
```

Moves head to branch => working repo is now in branch
```bash
git checkout "branch name"
```

Merge branch to main
```bash
checkout to main
git merge "branch name"
```

shows the status of git
```bash
git status
```



