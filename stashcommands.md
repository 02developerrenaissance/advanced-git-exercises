
# STASH COMMANDS LIST
# STASH ONLY SAVES FILES THOSE ALREADY TRACKED BY GIT 

git stash


git stash save "<Message or Name for stash for future refference>"


git stash list

o/p : prints list stash saved




git stash pop


o/p : removes latest stast and applies to the working area


git stash apply

git stash  apply stash@{<index>}
index : integer 0 to n



git stash show stash@{<index>}




#TO STASH UNTRACKED FILES

git stash --include-untracked

git stash --all
