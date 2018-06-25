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

<br>

### Save work without commit
> `git stash save "<message as a remainder>"`

<br>


### Show all stashed work
> `git stash list`

<br>

### Apply stashed work and keep in history
> `git stash apply <stash id>`

<br>

### Apply stashed work and delete from history
> `git stash pop <stash id>`

<br>

### Save untracked files without commit
> `git stash -u`

<br>

### Remove stash
> `git stash drop <stash id>`
##### *WARNING*: It may not be reversible
<br>

### Add ONLY all of the untracked files/directories to staging area
> `git add -i` then press `a` for untracked then `*` for all then `q` to quit and leave interactive area
<br>
