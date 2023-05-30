# Analyzing ARP Traffic In Wireshark
![](pexels.jpg)

## Introduction
This lab focuses on capturing and analyzing Address Resolution Protocol (ARP) data using Wireshark, a powerful network protocol analyzer.
ARP is used in TCP/IP networks to map layer 3 IPv4 addresses to layer 2 MAC addresses. By understanding ARP messages and analyzing them, one can troubleshoot network connectivity issues and gain insights into the device communication on a local network. 

## Objectives
1. Learning how to capture ARP traffic using Wireshark.
2. Examine IPv4 and Mac address information within the captured packets.
3. Explore contents of ARP messages exchanged between devices on the Local Area Network (LAN).
4. View ARP cache entries on Windows PC.

## Skills / Concepts Demonstrated
1. Wndows Command Prompt.
2. Hands on experience in using Wireshark to analyze network traffic.
3. ARP message analysis.
4. Troubleshooting network connectivity.

## Capturing ARP Data
### Retreiving PC interface addresses
The windows command prompt was used to issue the command **_ipconfig /all_** to get information on all network adapters including four very important address information needed for this lab. These are; the Mac address, IPv4 address, Default Gateway and the Subnet mask.

![](ConfigInfo.JPG)

**_Note_** : Two PCs connected to the same network were used for this lab. Below is the configuration information of PC2.

![](OtherPcConfig.jpg)

