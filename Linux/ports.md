2023.05.24

[Port tutorial](https://www.youtube.com/watch?v=g2fT-g9PX9o)

- a port is always associated with an [[IP address]]
- ports are assigned by the [[IANA]]
- a [[IP address]] and a port work together to exchange data on a network. 
   \<IP address\>:\<port\> e.g. 66.94.34.13:21
-  port number determines which service/program on the server, given by the [[IP address]], it wants to use. E.g. load web page "https://www.google.com". google.com gets by the computer converted into a [[IP address]] and [[HTTP 80]] into the port 80. ^6b5bf7
-  

### 3 Port categories
port number 0 - 1023 -> System- or [[Well-known ports]]
port number 1024 - 49151 -> User- or [[Registered ports]]
port number 49152 - 65525 -> Dynamic- or [[Private ports]]
### Common ports and Protocols
- [[TCP]]
	[[FTP 21]]
	remote machine:
	[[SSH 22 1]]
	[[Telnet 23 1]]
	mail:
	[[SMTP 25]]
	[[POP3 110 1]]
	[[IMAP 143 1]]
	URL to IP address:
	[[DNS 53 1]]
	websites:
	[[HTTP 80]]
	[[HTTPS 443]]
	
	[[SMB 139+445]]

- [[UDP]]
	[[DNS 53 1]]
	[[SHCP 67/68]]
	[[TFTP 69]]
	[[SNMP 161 1]]
	