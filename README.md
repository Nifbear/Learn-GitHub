# Learn-GitHub

Clone the repository to local:

```
git clone <link>
```

Check status

```
git status
```

Add file to queue to be committed later:

```
git add <file>
```

Commit: lock the file in repository in local

```
git commit -m 'message'
# commit all in queue
git commit -a  
```

Push online:

```
git push
```

Pull down the newest version:

```
git pull
```

Resolve Merge Conflicts:

```
# edit
git commit
git add -A
git commit
```

Force to pull all and ignore conflicts:

```
git fetch --all
git reset --hard origin/master
git pull
```

