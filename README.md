# GIT TUTORIAL
## How to install git ?
1.Go in to Official download [link](https://git-scm.com/downloads) <br>
2.Select your Option and Start Downloading.
> Example Window 32bit 64bit , linux, Mac Os etc
<br>
3.Install in computer.<br>
4.Check For version in the Terminal <br>
<br>

```
 git config --global user.name "github_username"
```

```
git config --global user.email "email_address"
```



<hr>
create branch 

```
git branch branch-Name
```

delete branch locally and globally 

```
git push origin --delete remoteBranchName
```

brach Merge
```
git checkout <brach were you want > 
git merge <branch from where you want >
```
----------------


```
echo "# s" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/suryaofficial7/s.git
git push -u origin main
```
