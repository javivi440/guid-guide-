## 1.   Config user 

```
git config --global user.name "Your Full Name"
git config --global user.email "your-email-address"
git config --list
```
## 2. Init git 
```
mkdir "Repository Name"
cd ".\Repository Name"
git init 
dir -hidden
```
## 3. First git
```
git status 
git add .\file.ext 
git status 
git comit -m "Commit message: brief description"
git status 
```


# 4. Create branch
```

git branch dir/branch-name 
git branch

```
## 5. Checkout branch
```

git checkout dir/branch-name 
git branch 

```
## 6. Merge to Master 
```
git checkout master
git status
git merge dir/branch-name
git status 
git log 

```