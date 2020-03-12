# git-aliases
A list of some useful aliases to use on git

### GIT LOG COMMITS DONE BY ME:
#### eg.: --author=everton
git config --global alias.my 'log --author=<your_name_here>' 

### ABOVE ABBREVIATED:
git config --global alias.lmy 'log --author=<your_name_here> --pretty=format:"%C(yellow)%h%Cred%d\\ %Creset%s%Cblue" --decorate' 

### ABOVE SHOW CHANGED FILES:
git config --global alias.myfiles 'log --author=<your_name_here> --pretty=format:"%C(yellow)%h%Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate --numstat'

### CHECKOUT MASTER:
git config --global alias.master 'checkout master'

### UNDO:
git config --global alias.undo 'reset HEAD~1 --mixed'

### SAVE TO STASH:
git config --global alias.undo 'stash save'

### APPLY LAST STASH:
git config --global alias.apply 'stash apply'

### POP STASH
git config --global alias.pop 'stash pop'
