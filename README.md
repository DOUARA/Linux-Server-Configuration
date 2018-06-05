# Description
Preparing a baseline installation of a Linux server to host web applications and securing it from a number of attack vectors.
The prepation includes installation and configuration of a database server and deployment of a python flask web application.
This project is for completion of Udacity's [Full-Stack Web Developer Nanodegree](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004).

# Server info
- IP Address: 192.99.55.117
- SSH Port: 2200
- URL for the application: http://vps186977.vps.ovh.ca/ ( Located on: /var/www/html )

# Software Installed: 
- OS: Ubuntu 16.04
- Database MS: PostgreSQL, SQLite. 
- Apcahe2 
- mod_wsgi 
- Python 2.7 
- python Flask framework
- SQLAlchemy ORM

 # Configurations 
 - Blocking the remote access for the root user
 - Configuring the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
 - Forcing Key-pair Authentication
 
 
 

