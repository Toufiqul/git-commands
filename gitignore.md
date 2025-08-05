#### Remove the files from the index (not the actual files in the working copy)
ignoring/deleting filed after adding them to git doesn't remove them. this is the way to remove them.
```
git rm -r --cached .
```

#### Add these removals to the Staging Area...
```
git add .
```

#### ...and commit them!
```
git commit -m "Clean up ignored files"
```
