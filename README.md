# linux-server-configuration

## Server details
* IP address: 35.162.67.134
* SSH-port: 2200
* URL: http://ec2-35-162-67-134.us-west-2.compute.amazonaws.com/

## Summary of software
* apache2
* libapache2-mod-wsgi
* postgresql postgresql-contrib
* git
* python-virtualenv
* python-pip 
* python-psycopg2
* libpq-dev
* python-dev

## Summary of configurations 
* Add user.
* Update software.
* Change password user.
* Give new user root access.
* Configure the local timezone to UTC.
* Update all currently installed packages.
* Change the SSH port from 22 to 2200.
* Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123)
* Install and configure Apache to serve a Python mod_wsgi application
* Install and configure PostgreSQL
* Create a new user named catalog
* Install git, clone and set up the Catalog App project

## List of third-party resources
* [How do I disable SSH login for the root user? - Media Temple](https://mediatemple.net/community/products/dv/204643810/how-do-i-disable-ssh-login-for-the-root-user)
* [No password prompt at sudo command - Ask Ubuntu](http://askubuntu.com/questions/153933/no-password-prompt-at-sudo-command)
* [RootSudoTimeout - Community Help Wiki](https://help.ubuntu.com/community/RootSudoTimeout)
* [command line - How to get sudo to prompt you for a password each time - Ask Ubuntu](http://askubuntu.com/questions/636092/how-to-get-sudo-to-prompt-you-for-a-password-each-time)
* [How To Install and Use PostgreSQL on Ubuntu 16.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04)
* [Flask by Example - Project Setup - Real Python](https://realpython.com/blog/python/flask-by-example-part-1-project-setup/)
* [How To Deploy a Flask Application on an Ubuntu VPS | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
* [PostgreSQL — SQLAlchemy 1.1 Documentation](http://docs.sqlalchemy.org/en/latest/dialects/postgresql.html)
* [Quickstart — Flask Documentation (0.12)](http://flask.pocoo.org/docs/0.12/quickstart/)
