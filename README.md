# Introduction to Git

>  Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. [Git web](https://git-scm.com/)

## Installation of git

For updated intructions check the [Atlassian Documentation](https://confluence.atlassian.com/bitbucket/set-up-git-744723531.html).

[git --fast-version-control](https://git-scm.com/downloads)

### Linux

[Download for Linux and Unix](https://git-scm.com/download/linux)

```
sudo apt-get install git
which git
```

### Windows

Download the Git for Windows [installer package](https://git-scm.com/download/win).
Run the installer
Use Git from Bash only
Checkout Windows-style, commit Unix-style line ending
Use MinTTY
Enable

If java is not recognized:
```
java
javac
```
Copy addres of where binaries of java and javac are found with semicolom
Program Files >> Java >> jdk >> bin 

on
windows >> control panel >> System and Security >> System >> 
Advanced System Settings >> Advanced >> Environment Variables >> Sytem variables >> Path
Next and Finish prompts to complete the installation.
Open Git Bash.vbs from the Git folder of the Programs directory to open a command window

### Mac

```
git --version
```
Download the Git installer from its official website.  
The installer is a DMG file. 
Double-click the DMG to expand it.
Double-click the PKG file to install it.
The Git installer launches.
Follow the prompts to install Git.
Open a terminal on your system.
Verify the installation was successful by typing which git --version at the command line.



> The easiest is probably to install the Xcode Command Line Tools. On Mavericks (10.9) or above you can do this simply by trying to run git from the Terminal the very first time. If you don’t have it installed already, it will prompt you to install it. [Install git on mac](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

```
Launch the App Store then download "Xcode".
Install Xcode, run it and go to Xcode’s preference via shortcut key `command` + `,`
Go to the Downloads tab, look for "Command Line Tools", and click Install.
quit and re-open Terminal, hit the git command and see if it has been successfully reinstated.
```

## Setting git and a web repository

### Linux

```
# Set up user.name for all the repositories.
git config --global user.name "Erick Chacon"

# Set up user.mail for all the repositories.
git config --global user.email "eral.th07@gmail.com"

# Check current user.name and user.email at once.
git config --list

# Check existing SSH keys.
ls -al ~/.ssh 
# public and private key pair listed (e.g. id_rsa.pub and id_rsa)

# Generate new SSH Key
ssh-keygen -t rsa -b 4096 -C "eral.th07@gmail.com"

# Adding SSH key to the ssh-agent.
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa

# Adding the new SSH key to GitHub account.
gedit ~/.ssh/id_rsa.pub # copy the content of the file
# Set a new SHH key on your GitHub settings.
```

### Windows

```
ssh-keygen -t dsa
cd ~/.ssh
ls -la
cat id_dsa.pub
git config --global user.name "Emma Paris"
git config --global user.email "eparis@atlassian.com"
```

## Git commands

### Clone a repository

### Create a branch

### Pull and push

### Merge branch with master repository

