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



* To access server locally in the ubuntu shell run

1. using the DNS name

![photo](Images/curllocal1.png)


2. using the public IP address

![photo](Images/curlip1.png)



