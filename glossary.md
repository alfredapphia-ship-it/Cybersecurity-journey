# My Glossary (one name per idea)

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
Switch - connects devices inside one network, works at layer 2
Firewall - allows or blocks traffic based on rules

## Process
Encapsulation - wrapping data in headers as it goes down the layers
Decapsulation - unwrapping it on the other side
