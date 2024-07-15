## Web Page Protocols

#### Hyper Text Transfer Protocol (HTTP)
* Used to access web pages 
* Default Port Number: 80

#### Hyper Text Transfer Protocol Secure(HTTPs)
* Used to access web pages and sensitive data, encrypting it
* Default Port Number: 443

## File Transfer Protocols
> Used to transfer files from one location to another

#### File Transfer Protocol (FTP)
* Transfer files, NOT ENCRYPTED
* Default Port Number: 21


#### Secure File Transfer Protocol Secure (SFTP)
* Transfer files, ENCRYPTED
* Default Port Number: 22

## Remote Access Protocols

#### Telnet 
> Teletype Network (or Telnet) is used to remotely control another device via console or command
shell. 

*  Telnet lets users configure network devices from almost anywhere worldwide so long as both devices have network connectivity. However, Telnet should not be used due to data being in clear text (no encryption). 
* The default port number: 23

#### Secure Shell (SSH)
> Used to remotely control another device via console or command shell securely with encryption.
* Default Port Number: 22 `same as SFTP as they both offer similar secured services`.

#### Remote Desktop Protocol (RDP)
> Used to remotely control another computer via a GUI
* Default Port Number: 3389

## Email Protocols
> Email protocols determine how email messages are received, stored, downloaded, removed,
or retained

#### Post Office Protocol (POP3)
> Older protocol that was the standard for receiving email. With POP3, email is downloaded
from an email server to a `single device`, and then the email is deleted from the server.
* Default Port Number: 110

#### Internet Message Access Protocol v4 (IMAP4)
> Protocol responsible for `receiving email`. With IMAP4, email is stored on the server and synchronized to `multiple devices`, like laptops and mobile phones.
* Default Port Number: 143


#### Simple Message Transport Protocol (SMTP)
> Responsible for `sending email`.
*  The default port for SMTP is 25.

## Network Protocols

#### Dynamic Host Configuration Protocol (DHCP)
> Dynamically allocates IP addresses to network devices that connects to a network

* IP addresses can be `statistically`, `dynamically` or `automatically allocated` via DHCP

* Default Port Numbers: 
    * DHCP client: 67
    * DHCP server: 68

#### Domain Name System (or DNS) 
> Resolves or translates domain names to IP addresses. 
* The default port for DNS is 53.

#### Server Message Block (or SMB) 
> Enables sharing files and printers on the network.* The default port for SMB is 137-139

#### Simple Network Management Protocol (or SNMP) 
> Monitors the network. 
* Default Port: 161

#### Lightweight Directory Access Protocol (LDAP)
> Allows directory services to store
and authenticate passwords, usernames, and accounts and share them over the network.
* Default Port: 389

> All in all there are `thousands of protocols` for security, communication and management