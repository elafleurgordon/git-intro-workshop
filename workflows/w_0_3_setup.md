# Setup


## Step 1:  Configure user (on local computer)

### Configure user name and email (lets Git know who you are)
<kbd> git config --global user.name "First Last"  </kbd>  
<kbd> git config --global user.email "myname@email.com"  </kbd>  

To verify these additions, type:  
<kbd> git config --list  </kbd>  

### Configure (terminal) editor of choice
<kbd> git config --global core.editor "nano -w"  </kbd> 

Other editor options can be found in [Setting Up Git](http://swcarpentry.github.io/git-novice/02-setup/)

---

## Step 2: Create Your Working Directory for Git Repos
Navigate to your home directory where you want to create a directory for the git work.   
<kbd> cd ~ </kbd>  

Create the directories:  
<kbd>  mkdir ds  </kbd>  
<kbd>  mkdir ds/gitsample </kbd>  
<kbd>  cd ds/gitsample </kbd>  
<kbd>  pwd </kbd>  
  
>my example
```bash
pwd
/Users/reshamashaikh
```
```bash
mkdir ds
mkdir ds/gitsample
cd ds/gitsample
pwd
/Users/reshamashaikh/ds/gitsample
```
