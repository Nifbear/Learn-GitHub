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
--- 

## Upload to GitHub
```
cd [dir]
git init
git add .
git commit -m "Files"
git remote add origin https://github.com/Nifbear/...
git push -u origin master
```

## Directory Tree
Example:

```bash
Main
├── Sub1
│   ├── Sub1.1
│   │   ├── Sub1.1.1.txt
│   ├── Sub1.2
│   └── Sub1.4
├── Sub2
└── Sub3
```


## Jupyter Notebook Theme
```
jt -t chesterish -f fira -tf georgiaserif -tfs 12 -fs 11 -cellw 85% -ofs 10 -lineh 160 -T
jt -r
```

## GCP
--------- Upload ---------
```
gcloud compute scp /Users/cino/Desktop/model.zip ecbm4040@instance-traffic:~/traffic
```
--------- Connect --------
```
gcloud compute ssh ecbm4040@instance-traffic
```
------ Connect Jupyter ---
```
gcloud compute ssh --ssh-flag="-L 9999:localhost:8888" --zone "us-east1-d" "ecbm4040@instance-traffic"
--------- Env ------------
```
source dlenv/bin/activate
jupyter notebook
```

