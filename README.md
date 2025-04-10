# NetPractice
42 School exercise to learn how to config networks based on IP addresses and subnet masks.

We only use the IPv4 norm in this exercise. In this norm,IP addresses are in 32-bit format.

- the IP address coupled with the subnet mask give you information on the network addresses range.

- the first address of a network represents the network address.
  
- the last address of a network  represents the broadcast address of the network.

- Switch connects computers to form a network

- Router connects different networks

# How to interpret Masks ?

The mask give us information on the part of the IP address that represents the network.

- Mask 255.255.255.0 means that 3 bytes are used to represent the IP address of the network.
- Mask 255.255.0.0 means that 2 bytes are used to represent the IP address of the network.
- Mask 255.0.0.0 means that 1 byte is used to represent the IP address of the network.

Example 1:
IP    1.1.1.1
Mask  255.255.255.0

- In this example, 3 bytes are representing the IP address of the network so 1.1.1.0 is the Network IP Address.
- the last byte of the mask indicating 0 means that the last byte of the IP Address if free to use.
- So the range of this network would be [1.1.1.0; 1.1.1.255] with
  - 1.1.1.0 Network IP Address
  - and 1.1.1.255 Broadcast address.


