# Introduction

This assignment report takes a look at the various core network terms explaining their uses with images.

# NAT (Network Address Translation)

Explanation: NAT (Network Address Translation) is a method used by routers to allow multiple devices on a private network (like your home Wi-Fi) to share a single public IP address to connect to the internet.

Real-World Example: Your home Wi-Fi router uses NAT to allow all your phones, laptops, and smart devices to connect to the internet using the single IP address your internet provider gives you.


<img width="800" height="310" alt="image" src="https://github.com/user-attachments/assets/f104e737-6454-4846-a867-f8c80e069d4e" />


# ARP (Address Resolution Protocol)

Explanation: When one device on a local network wants to send information to another device by its IP address, it needs to know the recipient's physical address (MAC address). ARP is like asking, "Hey, who at [IP address] lives here?" The device with that IP address will respond with its MAC address, allowing the sender to send the data to the correct physical hardware.

Real-World Example: When your computer on your home network wants to communicate with another computer on the same network (e.g., to share a file), it uses ARP to find the other computer's MAC address.


<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/d8371f17-ba00-46c6-9227-f4ab3afc3c6f" />


# MAC Address (Media Access Control Address)

Explanation: A MAC address is a unique, physical address assigned to each network interface card (NIC) or hardware that can connect to a network. Think of it as the permanent ID card for your device's network connection. It's like the serial number of your network adapter.

Real-World Example: Every device that can connect to a network (your computer's Wi-Fi adapter, your phone's Bluetooth, your smart TV's Ethernet port) has a unique MAC address assigned by the manufacturer.


<img width="298" height="169" alt="image" src="https://github.com/user-attachments/assets/086b7cb8-9449-43dd-86c7-fe4bf30e0672" />


# IPv4 (Internet Protocol version 4)

Explanation: IPv4 is the fourth version of the Internet Protocol and is the primary addressing system used on the internet. An IPv4 address is a 32-bit numeric address written as four numbers (octets) separated by dots. It acts like a logical address that identifies a device on a network.

Real-World Example: When you connect to the internet, your internet service provider (ISP) assigns your device an IPv4 address (or your router gets one). This address is used to route internet traffic to and from your device. A common example of a private IPv4 address is 192.168.1.100.


<img width="297" height="170" alt="image" src="https://github.com/user-attachments/assets/0c3583bd-9829-4a21-acf9-08c10f9e8535" />


# IPv6 (Internet Protocol version 6)

Explanation: IPv6 is the latest version of the Internet Protocol, created to address the limitations of IPv4 (specifically, the exhaustion of available addresses). An IPv6 address is a 128-bit address written as eight groups of four hexadecimal digits, separated by colons. It provides a much larger address space compared to IPv4.

Real-World Example: As more and more devices connect to the internet, IPv6 is being gradually adopted to provide a sufficient number of unique internet addresses. You might see IPv6 addresses in more modern network configurations. An example of an IPv6 address is 2001:0db8:85a3:0000:0000:8a2e:0370:7334.


<img width="648" height="648" alt="image" src="https://github.com/user-attachments/assets/bd34b4f7-e26f-4ed6-86fc-acc927e798df" />

# Conclusion

In today's interconnected world, understanding the language of networks is more important than ever. The five concepts we've explored—NAT, ARP, MAC, IPv4, and IPv6—are the fundamental building blocks that make modern digital communication possible.

