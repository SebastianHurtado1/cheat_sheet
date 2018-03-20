<center>

# Undo

</center>

### Reverse to specified commit safely
> `git reflog`

> `git revert <hash>`

<br>

### History of all commands
> `git reflog`

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

> `git cherrypick <hash>`

<br>

### Reverse to specified commit. Puts changes as STAGED
> `git reset --soft <hash>`
##### *WARNING: DO NOT use if others have pulled from your code. Changes commit history*

<br>

### Reverse to specified commit. Puts changes as UNSTAGED
> `git reset <hash>`
##### *WARNING: DO NOT use if others have pulled from your code. Changes commit history*

<br>

### Reverse to specified commit. Removes changes
> `git reset --hard <hash>`
##### *WARNING: DO NOT use if others have pulled from your code. Changes commit history* 

<br>

### Remove untracked file and directories
> `git clean -df`

<br>
