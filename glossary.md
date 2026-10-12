# My Glossary (DAILY ENTRIES OF THINGS I LEARNT IN MY DAY)
WEEK 1-DAY ONE-OSI MODEL
## The 7 layers (top to bottom)
7 Application - the programs you use (browser, email)
6 Presentation - formats and encrypts the data
5 Session - opens, keeps, and closes the conversation
4 Transport - splits data into pieces and delivers them (TCP or UDP)
3 Network - addresses and routes data between networks (IP)
2 Data Link - moves data between devices on the same network (MAC)
1 Physical - cables and wireless signals

## Data units (what the chunk of data is called at each layer)
Layer 4 = segment
Layer 3 = packet
Layer 2 = frame
Layer 1 = bits

## Addresses and ports
IP address - identifies a device on a network (layer 3)
MAC address - identifies a device's network hardware (layer 2)
Port - identifies which service on a device (layer 4), e.g. 443 = HTTPS

## Devices
Router - connects networks, works at layer 3

WEEK2-DAY TWO--IP ADDRESS AND COMMON PORTS
# Day 2: IP addresses, ports, and protocols

## What I studied
Resources: Professor Messer, Network+ course (Introduction to IP, Common Ports);
Claude (AI assistant) for explanations and checking my understanding

## What I learned
- IP address: identifies a device on a network
- MAC address: identifies a device's network hardware
- Port: identifies which service I want on a device
- Protocol: an agreed set of rules between sender and receiver
- IPv4: four groups of 0-255 separated by dots. IPv6: eight groups in hexadecimal
  separated by colons. IPv6 exists because IPv4 addresses ran out
- TCP (reliable, opens and closes a connection) vs UDP (fast, no connection)
- Common ports: HTTP 80, HTTPS 443 (secure, encrypted), DNS 53 (turns a name into an
  IP address), SSH 22 (secure shell, remote login), FTP (file transfer)
- Other protocols I met: Telnet, SMTP, SMB, Syslog
- A bit about SQL and databases (SQL is the language, MySQL is a database program)

## What confused me (and how I worked it out)
- IPv4 vs IPv6: the 4 and 6 are version numbers, not how many numbers an address has.
  IPv6 has eight groups, and "::" replaces a run of all-zero groups
- TCP vs UDP: TCP is like a phone call, UDP is like a postcard
- Sockets and ephemeral ports: a socket is IP + port, and an ephemeral port is a
  temporary port my device picks for one conversation
- Why there is a protocol for everything (calls, texts, web pages): any time two
  things need to understand each other, they use a protocol

## Questions I still have
- What is multiplexing?
- How are all these protocols integrated?
- Will I use all of these protocols in my day-to-day life as a cybersecurity analyst?
Switch - connects devices inside one network, works at layer 2
Firewall - allows or blocks traffic based on rules

## Process
Encapsulation - wrapping data in headers as it goes down the layers
Decapsulation - unwrapping it on the other side
