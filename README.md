# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

<img width="1224" height="744" alt="image" src="https://github.com/user-attachments/assets/9a514f3e-17ec-4446-b6c2-cb8020523d50" />

### Summary 

This output shows the use of the arp -a command in Windows Command Prompt to display the ARP table. The table lists IP addresses and their corresponding physical (MAC) addresses connected to the local network. This helps in identifying active devices and analyzing network communication during ARP attack and network sniffing experiments.

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:

<img width="816" height="281" alt="ettx" src="https://github.com/user-attachments/assets/371919fa-495c-47bc-8357-211222cee618" />

### Summary

This section demonstrates an ARP spoofing and network sniffing attack using tools like Ettercap and dsniff in Kali Linux.

Ettercap is used to scan and identify devices on the local network (showing IP and MAC addresses).
After identifying the target systems, dsniff is executed to capture and monitor network traffic.
The output shows ARP packets and duplicate address messages, indicating that ARP spoofing is being performed to intercept communication between devices.

Overall, the experiment explains how attackers can perform a Man-in-the-Middle (MITM) attack to sniff sensitive network data.

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="1919" height="368" alt="arpspoof" src="https://github.com/user-attachments/assets/fb81cac2-7136-45d7-be4d-e69afe7e2347" />

### Summary 

This experiment demonstrates the use of Kali Linux tools such as Ettercap, dsniff, and Wireshark for ARP attack and network sniffing analysis. The tools were used to identify devices, capture ARP packets, and monitor network traffic. The results confirm that ARP spoofing and packet sniffing activities were successfully analyzed in the network environment.


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
