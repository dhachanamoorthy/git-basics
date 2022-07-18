# git-basics
## Git Basic Commands


- Initialize git to service
```
git init
```
- To clone git from origin
```
git clone dhachanamoorthy@host:git-basics
```
- To commit Changes
```
git commit -m "commit message"
```
- To create branch
```
git checkout -b <branch-name>
```
- To switch to existing branch
```
git checkout <branch-name>
```
- To push branch to origin
```
git push origin <branch-name>
```
- To delete branch
```
git branch -d <branch-name>
```
- To update branch with remote changes
```
git pull
```
- To merge branch with active branch
```
git merge <branch-to-be-merged>
```
- To get only latest changes by discarding local changes
```
git fetch origin

git reset --hard origin/master
```

- To reset the commit to desired head
```
git reset --hard <commit-id>

git push origin <branch> -f
```

