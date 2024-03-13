`clone` <br/>
`git clone {repo link} {folder_name}` <br/>
`git clone {repo link} .` <br/>

```
add
commit
push
pull (pulls updated from remote)
status (see newly changed and added files)
ls | grep ${the part that will be matched with files}
init
```

### to add new files and updates

    git add .  (this will tell git to track all the files in the directory)
    or
    git add ${filename}
    git commit -m "message" -m "description"
    git commit -am "message" to add and commit with one command
    git push

### to generate rsa key pair

> ssh-keygen -t rsa -b 4096 -C "fahim.prime@gmail.com"

    (command ) -t(type of enc) -b(strength of enc) -C(mail)

> set name for key

    use passphrase(optional)
    (testkey and testkey.pub. .pub means public key)

> cat testkey.pub (to display the key in command line)
> copy and paste it to github->settings->ssh and gpg keys->new ssh key

    then might need to set it to local machine

### initiate a new repo

```
git init
git remote add origin ${new github repo link}
git add .
git remote -v (to check any remote repos connected to the directory)
might have to create main branch (git checkout -b main) or (*didnt work last time* git branch -M main)
git push -u origin main
 -u to set upstream, so , dont have to type origin main everytime. shortcut
```

### branch

```
 git branch (to see all the branches)
 git checkout -b ${name of new branch}
then add and commit the file to github and then
 git push -u origin ${name of branch}
 git branch -d ${name of branch}
 git commit -am "${message}" (does git add and commit at the same time; only works for files that are alrady added to git)
 git merge main (keep local main updated with remote main)
```

### pull request(merge request)
``` 
git pull {url of original repo}
```

> git merge master --allow-unrelated-histories

```
git show -${int value}
git log -${int value}
```

#### fork to copy a repo completely along with all the branches

### rename files

```
git mv {old file name} {new file name}
```

```

```
[This is a link](link here)
```