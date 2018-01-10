
## What is Git
Git is a distributed revision control and source code management system with an emphasis on speed. 
Git was initially designed and developed by Linus Torvalds for Linux kernel development. 
Git is a free software distributed under the terms of the GNU General Public License version 2.

### Features of Git
 
- Performance 
- Security 
- Flexibility
 
## Install Git 
- Install Git on Mac OS X 
- Install Git on Windows 
- Install Git on Linux 

 ```$ git credential-osxkeychain usage: git credential-osxkeychain <get|store|erase> ```

 ## Install Git on Linux 
 ` $ sudo apt-get update `  

` $ sudo apt-get install git `  

## Install Git on Mac OS x
- Download the latest [Git for Mac installer](https://sourceforge.net/projects/git-osx-installer/files/)

## Install Git on Windows
- Download the latest [Git for Windows installer](http://gitforwindows.org/)

## Git - Life Cycle

### [Git Life Cycle](https://www.tutorialspoint.com/git/images/life_cycle.png)

### Customize Git Environment

		git config --global user.name "username" 
		git config --global user.email "user-mail" 
		git config -- global  core.editor "editor_name" 
		git config --global color.ui auto 
		cat ~/.gitconfig

### create Repository

	git init --bare  "repo_name.git"
### Clone Repository
	git clone --local repo_name.git 
### change directory

	cd repo_name
### watch git status
	git status 
####  open new tab change directory
	cd git/repo_name
	watch git status 
update the changes continuously after two second.
