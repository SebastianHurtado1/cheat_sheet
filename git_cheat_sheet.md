<center>

# Undo

</center>

### Reverse to specified commit safely
> `git reflog`

> `git revert <commit hash>`

<br>

### Remove all changes that haven't been staged
> `git checkout <file>`

<br>

### Edit commit message 
> `git commit --amend -m "<new message>"`
##### *WARNING: DO NOT use if others have pulled from your code. Changes commit history*

<br>

### Add file after commit
> `git add`

> `git commit --amend`
##### *WARNING: DO NOT use if others have pulled from your code. Changes commit history*

<br>

### Grab commit from one branch to other
> `git checkout <branch>`

> `git cherrypick <commit hash>`

<br>

### Reverse to specified commit. Puts changes as STAGED
> `git reset --soft <commit hash>`
##### *WARNING: DO NOT use if others have pulled from your code. Changes commit history*

<br>

### Reverse to specified commit. Puts changes as UNSTAGED
> `git reset <commit hash>`
##### *WARNING: DO NOT use if others have pulled from your code. Changes commit history*

<br>

### Reverse to specified commit. Removes changes
> `git reset --hard <commit hash>`
##### *WARNING: DO NOT use if others have pulled from your code. Changes commit history* 

<br>

### Remove untracked file and directories
> `git clean -df`

<br>

<center>

# Commands to know

</center>

### History of all commands
> `git reflog`

<br>

### Show difference between commits
> `git diff <commit hash1> <commit hash2>`