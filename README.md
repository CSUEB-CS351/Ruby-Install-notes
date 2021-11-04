Windows 

Control panel open : “Programs” : “Turn Windows features on or off.” 
Scroll down to the bottom of the list and check the checkbox next to “Windows Subsystem for Linux,” then click “OK.” Then reboot the computer.

Windows Store and install Latest LTS Ubuntu (20.04)

Install and run Ubuntu

Update system:
	`sudo apt update`
	`sudo apt dist-upgrade`
	`sudo apt autoremove`
	`sudo apt clean`
	

https://github.com/rbenv/rbenv

`sudo apt install rbenv`
`mkdir .rbenv`
`mkdir .rbenv/plugins`
`cd .rbenv/plugins`
`git clone https://github.com/rbenv/ruby-build.git "$(rbenv root)"/plugins/ruby-build`


`sudo apt install build-essential patch ruby-dev zlib1g-dev liblzma-dev libsqlite3-dev nodejs`
`sudo apt install npm`

`rbenv install 2.7.4`

`gem list`







Mac:
https://brew.sh/
Terminal: 
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

https://github.com/rbenv/rbenv
`brew install rbenv`

`rbenv install 2.7.4`

Download and install Node.js
http://nodejs.org/en/download

`npm install --global yarn`

`gem install rails`
`mkdir web_development`
`cd to web_development`


`rails new firstApp`

sudo find / -name "psql"

nano ~/.zshrc
```
path+=('Library/PostgresSQL/14/bin/')
export PATH
```

or for bash

nano ~/.bash_profile
```
PATH=$PATH:/Library/PostgreSQL/9.4/bin
```	
	



