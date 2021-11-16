# Windows:

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

`npm install --global yarn`

`mkdir web_development`
`cd to web_development`
`rbenv local 2.7.4`

`gem install rails`
`gem install bundler`
`rbenv rehash`
`rails --version`

`rails new firstApp`

`sudo apt-get install postgresql postgresql-contrib libpq-dev`

`sudo /etc/init.d/postgresql start`

`sudo -u postgres psql` 

`create role [username] with createdb login password 'develop';`

`gem install pg`

`rails new MyPostgresqlApp --database=posgresql`






# Mac:
https://brew.sh/
Terminal: 
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

https://github.com/rbenv/rbenv
`brew install rbenv`

`rbenv init`

add `eval "$(rbenv init -)"` to your .zshrc file or .bashrc on old MacOS

to see stable verions of ruby you can install `rbenv install --list' or `rbenv install --list-all` to see the all 


`rbenv install 2.7.4`


Download and install Node.js
http://nodejs.org/en/download

`npm install --global yarn`

`mkdir web_development`
`cd to web_development`
`rbenv local 2.7.4`

`gem install rails`
`gem install bundler`
`rbenv rehash`
`rails --version`

`rails new firstApp`

`brew install postgresql`
`brew services start postgresql`
later to stop postgresql `brew services stop postgresql`
gem install pg
`rbenv rehash`


`sudo -u postgres psql` 
`create role [username] with createdb login password 'develop';`
`gem install pg`
`rails new MyPostgresqlApp --database=posgresql`


