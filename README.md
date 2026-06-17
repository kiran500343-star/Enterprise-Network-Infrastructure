# Enterprise-Network-Infrastructure
Enterprise network infrastructure design and implementation using Cisco Packet Tracer, featuring OSPF, EIGRP, routing, and network security concepts.
This project demonstrates the design and implementation of an enterprise network using Cisco Packet Tracer. The network is divided into multiple departments and uses dynamic routing protocols to ensure efficient communication between different network segments.
Technologies Used Cisco Packet Tracer,EIGRP Routing Protocol,OSPF Routing Protocol,Route Redistribution,IPv4 Addressing, ACL
EIGRP Network

The following departments are configured using EIGRP:

HR Department
accounting Department
development Department
training Department

The following departments are configured in OSPF Area 0:

Research and Development
Data Center
Cyber Security Department
Developer Department
OSPF Area 1

The following departments are configured in OSPF Area 1:

Distribution Department
Remote Office
Sales Management
Logistics and Supply Chain Department

ACL
Access control list is also applied for more security.the acl is applied in such a way that the HR can access any of the server but other department system can't access all the servers. there are servers such as the google, firefox ,ftp and dns servers these severs can be accessed any of the system
and there are totaly three department which are markeeting ,engineering and finace so there are specific servers to each department which can be accessed by the deparment system execpt for the HR department and here the port number 443 is used in tcp so the to access the site https:// need to be used 
