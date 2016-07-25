## Setting up git

To start using Git, it is required to create a user and a ssh-key for
authentication with the remote repository.

Set up user.name for all the repositories.
```
git config --global user.name "Erick Chacon"
```
Set up user.mail for all the repositories.
```
git config --global user.email "eral.th07@gmail.com"
```
Check current user.name and user.email at once.
```
git config --list
```
Check existing SSH keys.
```
ls -al ~/.ssh
```
*Public and private key pair listed (e.g. id_rsa.pub and id_rsa)*

Generate new SSH Key.
```
ssh-keygen -t rsa -b 4096 -C "eral.th07@gmail.com"
```
Adding SSH key to the ssh-agent.
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

Adding the new SSH key to GitHub account.
```
cat ~/.ssh/id_rsa.pub # copy the content of the file
```
Set a new SHH key on your GitHub settings.
