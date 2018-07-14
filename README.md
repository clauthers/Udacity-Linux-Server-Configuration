# Linux Server Configuration
This purpose for this project is run my Catalog Application in AWS Lightsail Ubuntu server that has been securely configured.

# 1. IP Address and port
The IP address is 52.200.75.126 and the port is 2200 for logging in.

# 2. Application URL
My catalog app URL is: http://www.52.200.75.126.xip.io

# 3. Summary of software installed and configuration changes made
Update all currently installed packages.
Change the SSH port from 22 to 2200 andconfigure the Lightsail firewall to allow it.
Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
Create a new user account named grader.
Give grader the permission to sudo.
Create an SSH key pair for grader using the ssh-keygen tool.
Configure the local timezone to UTC.
Install and configure Apache to serve a Python mod_wsgi application.
Install and configure PostgreSQL to not not allow remote connections.
Create a new database user named catalog that has limited permissions.
Install git.
Clone and setup your Item Catalog project from the Github repository.
Setup Item Catalog App in server so that it functions correctly when visiting server’s IP address in a browser. 
Make sure that .git directory is not publicly accessible via a browser.

# 4. Third-party resources I made use of to complete this project.
Udacity courses
https://www.topikettunen.com/2018/02/01/h3-linux-palvelimet-ict4tn021-8.html
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
http://www.bogotobogo.com/python/Flask/Python_Flask_HelloWorld_App_with_Apache_WSGI_Ubuntu14.php
http://leonwang.me/post/deploy-flask
http://terokarvinen.com/2017/write-python-3-web-apps-with-apache2-mod_wsgi-install-ubuntu-16-04-xenial-every-tiny-part-tested-separately
https://stackoverflow.com/questions/13189261/apache2-alias-not-working-in-ubuntu