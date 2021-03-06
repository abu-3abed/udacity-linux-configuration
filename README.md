# udacity-linux-configuration

Website info
------------
IP Address: [**http://18.197.188.214**](http://18.197.188.214)

Website URL: [**http://18.197.188.214.xip.io**](http://18.197.188.214.xip.io)

SSH port: 2200

Software Summary
----------------
OS: Ubuntu 16.04.6 LTS

Web Server: Apache Web Server (with mod_wsgi)

RDBMS: Postgresql

Programming Language: Python

Web Framework: Flask

Service Provider: Amazon Web Services (AWS)

hosting type: VPS

Configuration Summary
---------------------
1) changed default SSH port to 2200

2) made users login with public key auth only

3) made new user 'grader' with same privileges as root

4) used PostgreSQL to serve project's db instead of sqlite

5) made a new role 'catalog' in PostgreSQL to manage the db instead of superuser 'postgres'

6) made project.py (main project runner) acts as index.html

7) made .git folder hidden to internet users

Third Party Resources
---------------------
1) UNIX and Linux System Administration Handbook, 5th Edition

2) DigitalOcean

3) SQLALchemy

4) SSH Docs

5) Google Developers

6) Ubuntu Forums

7) StackExchange Websites

8) Medium

9) mod_wsgi Docs

10) Flask Docs

11) Liquid Web Knowledge Base

12) tableplus.io

13) github

14) Apache HTTP Server Docs

15) Python Docs

16) computerhope.com

17) Rackspace support

18) staff.washington.edu

19) Ubuntu Wiki

20) www.linode.com

21) kb.iu.edu

22) sudo.ws

23) www.linuxquestions.org

24) tutorials.ubuntu.com

25) linuxize.com
