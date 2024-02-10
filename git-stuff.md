## Branch workflow
Feature branch > Dev > Staging > Master/Prod

## Coding workflow
#### Fetch-Merge method[^1]
```
1. git checkout dev
2. git fetch
3. git pull
4. git checkout -b <feature branch name (apply workplace naming convention)>
5. <do your work>
6. git add .
   - or do a more selective and manual staging of files if necessary
7. git commit -m "<commit message (apply workplace naming convention)>"
8. git fetch origin dev (make sure you're feature branch works and is compatible with the current version of dev in case other changes were pushed before yours)
9. git merge origin/dev
10. resolve merge issues if there are any
11. git add .
12. git commit -m "<commit message for the merge>"
13. git push --set-upstream origin <feature branch name>
```
#### Pull-Merge method[^1]
```
text
```

#### Rebase method[^2]
```
text
```

[^1]:https://stackoverflow.com/questions/52107252/how-to-take-latest-changes-from-dev-branch-to-my-current-branch
[^2]:https://stackoverflow.com/questions/67930342/managing-changes-from-develop-branch-into-feature-prior-to-push-git
