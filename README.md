# github_ssh
# how to connect on github ssh

### step 1
```bash
git config --global credential.helper cache 
```

### step 2
```bash
ssh-keygen -t ed25519 -C "email"
```
### step 3
join in the directory
cat ssh/id_ed25519.pub

### step 4
get the key and put it in the github 
