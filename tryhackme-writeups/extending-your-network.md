### Morgan Albright

TryHackMe Room: Extending Your Network Difficulty Level: Walkthrough

Task 1: Introduction to Port Forwarding

## What is the name of the device that is used to configure port forwarding?

	The answer is listed at the very bottom. "Port forwarding is configured at the ______ of a network."

Task 2: Firewalls **101**

## What layers of the OSI model do firewalls operate at?

For this answer, just provide the numbers in ascending order, separated by an ampersand (&) I.e: 4 & 5

	Based on my knowledge of the **OSI** model from other rooms (Network and Transport Layers), I came to the conclusion the firewalls operate at *_ & _*

## What category of firewall inspects the entire connection?

	"If a connection from a host is bad, it will block the entire device." This helped me conclude it was ________.

## What category of firewall inspects individual packets?

	This one is exactly the opposite of the previous. "This firewall type uses a static set of rules to determine whether or not individual packets are acceptable or not" this helped me decide it was _________.

Task 3: Practical - Firewall

## What is the flag?

	To find the flag I did the practical simulation and blocked the packets from reaching the server so it wouldnt overload. The flag was **THM**{________}

Task 4: **VPN** Basics

## What VPN technology only encrypts & provides the authentication of data?

	When looking through the different types of vpn tech, I see "This technology is not capable of leaving a network by itself (non-routable)." This is why I went with ___

## What VPN technology uses the IP framework?

	It's literally in the name, however the description for it says "	
Internet Protocol Security (IPsec) encrypts data using the existing Internet Protocol (IP) framework." thats why I came to the conclusion _____.

Task 5: **LAN** Networking Devices

## What is the verb for the action that a router does?

	"It's a router's job to connect networks and pass data between them. It does this by using routing (hence the name router!)." That's how I came to the conclusion ______.

## What are the two different layers of switches? Separate these by a comma I.e.: Layer X,Layer Y

	"Switches can operate at both layer 2 and layer 3 of the **OSI** model. However, these are exclusive in the sense that Layer 2 switches cannot operate at layer 3." this is how I came to my conclusion _____ _, _____ _.

Task 6: Practical - Network Simulator

## What is the flag from the network simulator?

	What I did was send a tcp packet from computer 1 to computer 3. That's how I got **THM**{insert_flag_here}

## How many HANDSHAKE entries are there in the Network Log?

	I counted the handshake logs after I received my flag and that's how I got _.
