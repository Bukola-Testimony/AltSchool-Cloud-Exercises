  # AltSchool-Cloud-Exercise-10-Week-8


> ![AltSchool Cloud Exercices](../cloud3.JPG) 

<br>

- [Back to first page](../README.md)
- [📔 Exercise 1](../README.md)
- [📔 Exercise 2](../Exercise-2/exercise2.md)
- [📔 Exercise 3](../Exercise-3/exercise3.md)
- [📔 Exercise 4](../Exercise-4/exercise4.md)
- [📔 Exercise 5](../Exercise-5/exercise5.md)
- [📔 Exercise 6](../Exercise-6/exercise6.md)
- [📔 Exercise 7](../Exercise-7/exercise7.md)
- [📔 Exercise 8](../Exercise-8/exercise8.md)
- [📔 Exercise 9](../Exercise-9/exercise9.md)
- [Overview](#overview) 
- [Task](#Task-EXERCISE-10) 
- [My process](#my-process)
- [Author](#author)


<br>

## Overview
### LEARNING CLOUD ENGINEERING WITH ALTSCHOOL.
<p>
It's about 2 months of learning cloud engineering with AltSchool.There has been so many new concepts to learn. This is the last week in september.
</p>

<p>This week we learnt about Networking which refers to interconnected devises such as PC, smartphones, routers etc that can exchange data and share resources with each other. This connected devises use a system of rules called communication protocols to transmit information over physical or wireless devices.  
</p>

<p>All systems on a network  require IP addresses through which they can be identified. These are Public and Private IP addresses.
</p>  
<p>The internet connects the globe together through shared connection using cables. Routers on the other hand directs traffic to where it should go.
</p>  

<br>
<br>

## Some Networking Terms:

- Subnet Mask: 
A Subnet mask is a 32-bit number that masks an IP address, and divides the IP address into network address and host address. Subnet Mask is made by setting network bits to all "1"s and setting host bits to all "0"s. Within a given network, out of the total usable host addresses, two are always reserved for specific purposes and cannot be allocated to any host. These are the first address, which is reserved as a network address (a.k.a network ID) and the last address used for network broadcast.

- Router:
A router is a physical or virtual appliance that passes information between two or more packet-switched computer networks. A router inspects a given data packet's destination Internet Protocol address (IP address), calculates the best way for it to reach its destination and then forwards it accordingly.

- Private IP: 
Private IP addresses are assigned to the hosts in the same network to communicate among one another. As the name "private" suggests, the devices having the private IP addresses assigned can't be reached by the devices from any external network. For example, if I am living in a hostel and I want my hostelmates to join the game server I have hosted, I will ask them to join via my server's private IP address, since the network is local to the hostel.






## Task EXERCISE 10💻

## Given a network Address of: 193.16.20.35/29 
### find: 
- Network IP 
- Number of hosts
- Range of IP addresses
- Broadcast IP from this subnet

<br>
<br>


## My process
- I converted the decimal network numbers to binary digits.
- Based on the CIDR block I established the class and Netmask.
- Based on the netmask I calculated the wildcard. 
- Based on the wildcard I calculated the network IP. 
- Then I calculated the Broadcast IP 
- With the network IP and Broadcast IP I was able to find the range of IP address.
- Finally I calculated the number of hosts based on the IP range.

<br>
<br>

## Network Address given: 193.16.20.35/29 

## Adress (converted to binary) = 11000000.00010000.00010100.00100011

## Netmask: 255.255.255.248

## Wild card : 0.0.0.7

## Network IP: 193.16.20.32/29

## Broadcast IP: 193.16.20.39

## Host min: 193.16.20.33

## Host mxn: 193.16.20.38

## Host/Nets = 6 (Private Internet)


<br>
<br>

## Author

- Website - [Bukola Testimony](https://bukola-testimony.github.io/My-Portfolio-website/)
- Twitter - [@BukolaTestimony](https://twitter.com/BukolaTestimony)





