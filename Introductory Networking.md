# Introductory Networking room
# [Room](https://tryhackme.com/room/introtonetworking)
## Task2:The OSI Model: An Overview

### Q1:Which layer would choose to send data over TCP or UDP?
   A:4
### Q2:Which layer checks received packets to make sure that they haven't been corrupted?
A:2
### Q3:In which layer would data be formatted in preparation for transmission?
A:3
### Q4:Which layer transmits and receives data?
A:1
### Q5:Which layer encrypts, compresses, or otherwise transforms the initial data to give it a standardised format? 
A:6
### Q6:Which layer tracks communications between the host and receiving computers? 
A:5
### Q7:Which layer accepts communication requests from applications? 
A:7
### Q8:Which layer handles logical addressing?
A:3
### Q9:When sending data over TCP, what would you call the "bite-sized" pieces of data?
A:Segments
### Q10:[Research] Which layer would the FTP protocol communicate with?
A:7
### Q:Which transport layer protocol would be best suited to transmit a live video?
A:udp

## Task3:Encapsulation

### Q:How would you refer to data at layer 2 of the encapsulation process (with the OSI model)?
A:Frames
### Q:How would you refer to data at layer 4 of the encapsulation process (with the OSI model), if the UDP protocol has been selected?
A:Datagrams
### Q:What process would a computer perform on a received message?
A:De-encapsulation
### Q:Which is the only layer of the OSI model to add a trailer during encapsulation? 
A:Data Link
### Q:Does encapsulation provide an extra layer of security (Aye/Nay)? 
A:Aye

## Task 4:The TCP/IP Model    

### Q:Which model was introduced first, OSI or TCP/IP?
A:TCP/IP
### Q:Which layer of the TCP/IP model covers the functionality of the Transport layer of the OSI model (Full Name)?
A:Application
### Q:The Network Interface layer of the TCP/IP model covers the functionality of two layers in the OSI model. These layers are Data Link, and?.. (Full Name)?
A:Physical
### Q:Which layer of the TCP/IP model handles the functionality of the OSI network layer?
A:Internet
### Q:What kind of protocol is TCP?
A:Connection-based
### Q:What is SYN short for?
A:Synchronise
### Q:What is the second step of the three way handshake?
A:SYN/ACK
### Q:What is the short name for the "Acknowledgement" segment in the three-way handshake?
A:ACK

## Task 5:Networking Tools Ping

### Q:What command would you use to ping the bbc.co.uk website?
A:ping bbc.co.uk

### Q:Ping muirlandoracle.co.uk What is the IPv4 address?
A:217.160.0.152

### Q:What switch lets you change the interval of sent ping requests?
A:-i

### Q:What switch would allow you to restrict requests to IPv4?
A:-4

### Q:What switch would give you a more verbose output?
A:-v

## Task 6:Networking Tools Traceroute.

### Q:What switch would you use to specify an interface when using Traceroute?
A:-i.
### Q:What switch would you use if you wanted to use TCP SYN requests when tracing the route?
A:-T
### Q:[Lateral Thinking] Which layer of the TCP/IP model will traceroute run on by default (Windows)?
A:Internet

## Task 7:Networking Tools WHOIS.

### Q:What is the registrant postal code for facebook.com?
A:94025
### Q:When was the facebook.com domain first registered?
A:29/03/1997
### Q:Which city is the registrant based in?
A:Redmond
### Q:[OSINT] What is the name of the golf course that is near the registrant address for microsoft.com?
A:Bellevue Golf Course
### Q:What is the registered Tech Email for microsoft.com?
A:msnhst@microsoft.com

## Task 8:Networking Tools Dig

### Q1:What is DNS short for?
A:Domain Name System
### Q2:What is the first type of DNS server your computer would query when you search for a domain?
A:Recursive
### Q3:What type of DNS server contains records specific to domain extensions (i.e. .com, .co.uk*, etc)*? Use the long version of the name.
A:Top-Level Domain
### Q4:Where is the very first place your computer would look to find the IP address of a domain?
A:Local Cache
### Q5:[Research] Google runs two public DNS servers. One of them can be queried with the IP 8.8.8.8, what is the IP address of the other one?
A:8.8.4.4
### Q5:If a DNS query has a TTL of 24 hours, what number would the dig query show?
A:86400
