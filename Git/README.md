# Git

```shell
# check what's been modified and staged
git status

# add file or directory to next commit
git add file.php

# view staged files
git ls-files --stage

# remove staged file
git reset HEAD -- path/to/file

# remove file
git rm file.php

# remove directory
git rm -r directory

# removed cached file
git rm -r --cached file.php

# commit changes
git commit -m "change note"

# push file to Github (or a different remote)
# remote will be the SSH link on your repo
git push remote:master

# create a tag
git tag TAGNAME
# or
git tag -a TAGNAME -m "tag name"

# push the tag to the desired remote
git push remote TAGNAME
```
