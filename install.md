## Installation of Git

Downloads for Mac OS X, Windows, Linux and Solaris can be found on the official web of [git - downloads](https://git-scm.com/downloads). Instructions to install Git for Linux, Mac and Windows, using these downloads, are described on the [Atlassian Documentation - Set up Git](https://confluence.atlassian.com/bitbucket/set-up-git-744723531.html).

#### Linux

For Debian/Ubunto distribution, use the next command to install Git:
```
sudo apt-get install git
```

If your linux distributions is other, find distribution-specific instructions on [Download for Linux and Unix](https://git-scm.com/download/linux).

Finally, you can check if Git has been installed with:
```
which git
# /usr/bin/git
```

#### Windows

1. Download Git installer for Windows [installer package](https://git-scm.com/download/win).
2. Run the installer.
3. Select the location of the installation and proceed.
4. Select *Use Git from Bash only*.
5. Select *Checkout Windows-style, commit Unix-style line ending*.
6. Select *Use MinTTY*
7. Select *Enable ...*
8. Open **Git bash** on Programs directory to open a command window.

Note: If *java* is not recognized when typing `java` or `javac`, copy the address where binaries of java and javac are found (Program Files >> Java >> jdk >> bin) on:

> windows >> control panel >> System and Security >> System >> Advanced System Settings >> Advanced >> Environment Variables >> Sytem variables >> Path

*Do not forget to use semicolom to add the path.*

Open **Git bash** again and type `java`. It should be recognized now.

#### Mac

Check if Git is installed on your system.
```
git --version
# git version 2.1.4
```
###### Easiest installation of Git:

> The easiest is probably to install the Xcode Command Line Tools. On Mavericks (10.9) or above you can do this simply by trying to run git from the Terminal the very first time. If you don’t have it installed already, it will prompt you to install it. [Install git on mac](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

###### Installing Git through Xcode: [Install Xcode](http://www.hongkiat.com/blog/mountain-lion-git-fix/)

1. Launch the App Store, then download "Xcode".
2. Install Xcode, run it and go to Xcode’s preference via shortcut key `command` + `,`.
3. Go to the Downloads tab, look for "Command Line Tools", and click Install.
4. Quit and re-open Terminal, hit the git command and see if it has been successfully reinstated.

###### Manual installation of Git: [set-up-git](https://confluence.atlassian.com/bitbucket/set-up-git-744723531.html).

2. Download the Git installer from [git - download - mac](https://git-scm.com/download/mac). The installer is a DMG file. 
3. Double-click the DMG to expand it.
4. Double-click the PKG file to install it.
5. The Git installer launches.
6. Follow the prompts to install Git.
7. Open a terminal on your system.
8. Verify the installation was successful by typing which `git --version` at the command line.
