# Milestone 5
## Config Files
- [Mail](/Configs/Mail)
- [Web Server](/Configs/WebServer/)
- [Nextcloud](/Configs/Nextcloud/)
- [Database](/Config)
## Proof Of Work
**Mail:**
![an image of thunderbird showing emails recieved](/Screenshots/mail.png)

**Web Server:**
- [Changes Made](ChangesMade.md)

**Nextcloud:**
![a gif showing uploading a file to the storage server](/Screenshots/fileserver.gif)

**Database:**
![a screenshot of the databases and the tables used for the website](/Screenshots/database.png)

**Greenbone:**
![Greenbone scan results image 1](/Screenshots/Greenbone.png)
![Greenbone scan results image 2](/Screenshots/Greenbone2.png)

This README describes our practices for our specific configurations for the various services for Milestone 5.
The practices that were used when we set these configs up are really just general security practices. 
For networking purposes, we closed all unnecessary ports as well as whitelisted all the proper IP addresses.

We ensured all proper file permissions were set in place to prevent all unauthorized access to sensitive information.
We have confident and proper backup configurations to ensure that we aren't loosing important information and files that are crucial to our opperations.
We have setup firewalls to ensure only certain trafic that we want to get through is able to get through. This prevents unauthorized remote access to our systems.

Lastly, we have deployed the Greenbone vulnerability scanning tool across our entire network. This ensures that if anything unauthorized, or even mildly worrysome, happens on any of our systems, we will be able to see it quickly and take
action to prevent against further harm or risk that could significantly harm the company.
