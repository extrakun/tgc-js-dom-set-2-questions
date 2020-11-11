```
Checkout

git checkout --orphan latest_branch

Add all the files

Delete unwanted files

find . -type f -name 'solutions.js' -exec rm {} +

git add -A

Commit the changes

git commit -am "commit message"

Delete the branch

git branch -D master

Rename the current branch to master

git branch -m master

Finally, force update your repository

git push -f origin master
```