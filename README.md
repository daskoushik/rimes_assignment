# Rimes Solution Architect Assignment

There are 5 systems: 

S1: running a Linux based standalone applica�on with MySQL in local network, share data to S2. 

S2: running a PHP/MySQL Web application in local/public network, receive data from S1. 

S3: running a PHP/PostgreSQL Web application in local network, share data to S5 

S4: running a Python/Django/SQLite3 Web application in local network, share data to S5 

S5: running a Java Web application in local/public network, receive data from S3/S4 

Requirements: 

The systems need to run 24x7. 
End users need to be able to visit all systems from public network. 
Backup all systems weekly. 

Questions:

1. If there are two physical servers available and one public network connection, please: 
a. Provide a physical servers plan for all systems. 
b. Provide a systems architecture. 
c. Provide a network design for all systems. 

2. If there are no limited in physical servers and two public network connections available, please: 
a. Provide your best prac�ce designs and architectures to manage and handle all servers 
and systems.

You can use: 
Any opensource tools you need in your solution. 
Any quantity of routers you want to use in your network design.  
Any UML diagram to explain your ideas and architecture.
