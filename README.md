# Deploy a Linux Web Server (without AWS EC2)

A beginner project where I set up a working web server on Ubuntu (WSL) using Nginx.

## Tools used
- Ubuntu on WSL (Windows Subsystem for Linux)
- Nginx web server
- nano text editor

## Steps
1. Updated packages: `sudo apt update`
2. Installed Nginx: `sudo apt install nginx -y`
3. Started the server: `sudo service nginx start`
4. Checked it was running: `sudo service nginx status`
5. Tested it: `curl localhost` and opened http://localhost in Chrome
6. Created my own page in `/var/www/html/index.html`
7. Removed the default Nginx welcome page

## Result
My custom page is served by Nginx at http://localhost

## What I learned
- Basic Linux commands (cd, ls, cp, mv, nano, sudo)
- How to install and manage a service
- Where a web server keeps its files
- How to reset a WSL user password
