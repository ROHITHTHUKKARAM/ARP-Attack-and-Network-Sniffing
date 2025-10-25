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
<img width="1058" height="659" alt="Screenshot 2025-10-06 094416" src="https://github.com/user-attachments/assets/4f24234a-112a-4104-92e4-53285f9ba602" />


 From kali linux issue the command : sudo arpspoof -i eth0 -t
## OUTPUT:

<img width="1920" height="1080" alt="kali linux  Running  - Oracle VirtualBox 06-10-2025 09_47_00" src="https://github.com/user-attachments/assets/f00f87c8-ade5-40dd-b604-1a27b416e17e" />



In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1920" height="1080" alt="kali linux  Running  - Oracle VirtualBox 06-10-2025 09_54_45" src="https://github.com/user-attachments/assets/7bb69b67-b4ba-4a7d-a1d3-9190c4dce909" />



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
