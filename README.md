# git-tutorial
A repository for hosting the README for the git tutorial

## Workspaces

I would highly prefer if everyone used VSCode, but Atom is acceptable. If you know how to use another IDE
feel free to use that one too.

## Github SSH key
You will need a SSH key for this.

### Check if you already have a key / Print out public key
```
cd ~
cat .ssh/id_rsa.pub
```
If you already have a key that will print your public key out. If you get a no file error, run the below:

### If you do not have a key
```
cd ~
ssh-keygen
```
Then literally just press enter until its done.

###
Then add this key to github.
