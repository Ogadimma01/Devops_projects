# Prerequisites

* Launching an EC2 instance

![photo](Images/EC2.png)



* Connectiong to EC2 instance from Git bash terminal

![photo](Images/EC2connect.png) 

* Wnenever an EC2 instance is stopped and started again, a new IP address is generated so the ssh credentials must be updated in order to connect to the EC2 instance


# Installing Apache and Updating the Firewall

![photo](Images/apacheupd.png)

![photo](Images/apacheinst.png)


* Verify thhat Apache2 is running as a service on the OS

![photo](Images/apache2.png)


* To enable traffic to web server, add a rule to EC2 connection to open inbound connection through port 80

![photo](Images/port80.png)


* Once installation is complete,confirm PHP version


* To access server locally in the ubuntu shell run

1. using the DNS name

![photo](Images/curllocal1.png)


2. using the public IP address

![photo](Images/curlip1.png)


* To test response of Apache HTTP server to a internet request:

  Open a web browser and search for the following url: http://<public ip address>


![photo](Images/webpage.png)

If the above web page is returned, then the server has correctly installed and accessible through the firewall.


# Installing Mysql

![photo](Images/mysql.png)


* To log into mysql server  as administrative database root user.


![photo](Images/mysql2.png)


* Running interactive script


![photo](Images/Mysqlsec.png)


* Logging into Mysql using changed root user password.


![photo](Images/mysql-p.png)


* Exiting mysql.


![photo](Images/mysqlexit.png)


# Installing php

* php is available on Ubuntu Linux, but unlike Python (which comes pre-installed), must be manually installed.

* Before installing php you should install Apache (or a preferred web server) and a database service such as MySQL

* In addition to php, you'll need php-mysql, a php module that allows communication between php and mysql-based databases and libapache-mod-php
  to enable apache handle php files. Core PHP packages will automatically be installed as dependencies.


![photo](Images/phpinst1.png)


![photo](Images/phpinst2.png)


* Once installation is complete, confirm php version <php -v>


![photo](Images/php-v.png)




  



