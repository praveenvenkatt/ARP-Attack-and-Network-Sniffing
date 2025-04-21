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

```
Register Number: 212222040121
Name: Praveen V
```

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![{1E114702-7D0C-41F0-B1B3-A2B98F54F68D}](https://github.com/user-attachments/assets/bbe46d6f-3455-445b-a280-a1ce4bf618ad)




From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> -r  <gateway>
eth0 should replaced by appropriate interface from iconfig command
## OUTPUT:
![{40DA96F4-9C8B-470F-A10A-0E7D313D2841}](https://github.com/user-attachments/assets/f56aabcf-3695-497f-83b7-d432191c814a)



 dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![{9B9B97A1-C13E-49A1-848C-C211DFD6E9C2}](https://github.com/user-attachments/assets/7e40450b-11de-452c-9139-2d74d6038a15)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![{19A13A7D-182F-47A3-8C91-FEEE6D5EDFAF}](https://github.com/user-attachments/assets/f9107e84-ce1b-4618-87c7-033cae18617b)



Invoke the wireshark and examine the various menus  and controls of the tool. Also following shows how wireshark can be used as sniffing tool.
![{495B0136-5A90-4BA1-8725-BAE5D24B6A65}](https://github.com/user-attachments/assets/9a31cf37-8a6e-4762-abe0-a158278af752)


##Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
