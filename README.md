# network-design

-	The entire project is using VLSM for subnetting. There are 4 routers in total for multiple branches and a headquarters which are HQ(HeadQuarter), JB(Johor Bahru), GT(GeorgeTown) and KT(Kuala Terengganu).

-	For every division of each branch will be assigned a switch and naming by using their department’s name such as HQ_Finance, etc. 

-	For every branches’ division and subdivisions, they will be assigned dhcp based on their IP range, except servers were static IP. 

-	Cables
Three types of cables are being used which are Copper Straight-Through, Copper Cross-Over and Serial DCE. 
Copper Straight-Through Cable - used to connect Router to Switches, switches to PC.
Copper Cross-Over Cable - used to connect Switches to Switches
Serial DCE - used to connect between router 

-	DHCP
DHCP server is configured in Management & Admin in Kuala Lumpur which is the headquarters(HQ) of the company. For every branch or division, DHCP will assign the IP for the PC automatically based on their subnet accordingly. 

-	DNS Server
The DNS server is configured in the Marketing & Sales department of Kuala Lumpur which is the headquarters(HQ) of the company. It will return the ip addresses of the domains upon DNS requests.


-	Email Server
One of the email servers is configured in the Customer Service department of Kuala Lumpur which is the headquarters (HQ) of the company. The other email server is combined with the DNS server which configured in the Marketing & Sales department of HQ.  It allows all users to send emails to each other. 
1st Domain Name : pmail.com
2nd Domain Name: gmail.com

-	IoT Server
The Iot Server is configured in the Finance department of Kuala Lumpur which is the headquarters(HQ) of the company. It can control the status of the IoT devices such as motion detector, light, fan, and coffee machine.
SSID : PowerPuff
PSK Pass Phrase: PowerPuff
Username: PowerPuff
Password:1234
 



-	Web browser
There is a Web Server configured in the HQ’s finance department. Every branches which included Johor Bahru(JB), Kuala Terengganu(KT), GeorgeTown(GT) are able to access to the browser which was www.powerpuff.com

-	Network security 
1.	Password	
User authentication is required before access to the router.
Secret passwords were enabled to every single router in our project which included HQ, JB, KT as well as GT  in order to provide an additional layer of security over the enable password command in global configuration mode.
Username : admin
Password : ppg

2.	Access Control : 
Blocked JB_ShowroomCS from the network. 

