# docker-stack
A development stack that comes with nginx, php 7.4, mysql and phpmyadmin

## Features
- nginx
- PHP 7.4
- mysql
- phpmyadmin
- xdebug support
- phpunit support
- yarn support


## Usage
When you cloned the repo first thing would be to customize your .env file. 
The default configuration sets xdebug up for windows usage.

After that you simply run `docker-compose up -d`. First time you do this it will build the dockerfile based image for the php container and start up the containers afterwards.

Your code goes into the app/public folder.