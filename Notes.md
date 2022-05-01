# "Turkcell Siber Güvenliğin Süper Kadınları" Program --> Notes from Introduction to Cyber Security Lesson

### ***Link:*** 
```
https://gelecegiyazanlar.turkcell.com.tr/superkadinlar
```
#

- **GNU/Linux**

<p>&nbsp;</p>

- **hacker methodology** (Of course first “Permission” 1-information gathering, 2-threat modeling(Nmap), 3-vulnerability analysis, 4- exploitation, 5- post-exploitation(backdoor), finally reporting) 

<p>&nbsp;</p>

- **Malware** (Virus, Trojan, Worm, Spyware and Adware, Ransomware, Cryptojacking, scareware)

<p>&nbsp;</p>

- **Denial-of-service(DOS)**, **Distributed Denial of Service(DDOS)**, **Spoofing**, **Man in the Middle(MITM)**, **active and passive scanning**

<p>&nbsp;</p>

- **Linux basic terminal commands** such as 
  - *pwd(print working directory)*
  - *ls(list files or directories)*
  - *cd (change directory)* 
  - *touch (creating a file)*
  - *cat (Reading file)* 
  - *rm(remove the file)* 
  - *mkdir(make directory)* 
  - *rm -rf (remove the folder)*

<p>&nbsp;</p>

- **nano** Linux text editor (primitive but very useful)

<p>&nbsp;</p>

- **chmod(change mode)** → drwxr-xr-x firstfile.txt → d means directory, r means to read, w means to write and x means to execute. We look at it in 3 blocks of code such as rwx, r-x, and r-x (we will ignore the first part, d or dash, because it gives us the meaning of directory or file). The first 3 blocks of code give information about what the user can do, the second 3 blocks of code give information about what the group can do and the last 3 blocks of code give information about what the reaming users can do. 

<p>&nbsp;</p>

- **ifconfig (interface configuration**)** → IP, MAC, netmask, etc. shows our status and interfaces within the network

<p>&nbsp;</p>

- **Network Hardware:** NIC(Ethernet Card), Switch, Firewall, and Router.  

<p>&nbsp;</p>

- **The network** is divided into two according to its size: LAN(Local Area Network) and WAN(Wide Area Network)

<p>&nbsp;</p>

- **TCP/IP (Transmission Control Protocol/ Internet Protocol)**

<p>&nbsp;</p>

- **The IP address** consists of two parts **Network ID** and **Host ID** (For example IP address: 192.168.32.170 - 192.168.32 is the Network ID and 170 is the Host ID)

<p>&nbsp;</p>

- **Subnet Mask** → It is the factor that determines the network ID and Host IDs.It is the IP address classes that determine the subnet mask. Each IP has a Subnet Mask and class.


<p>&nbsp;</p>

- **cidr(Classless Inter-Domain Routing) notation**

<p>&nbsp;</p>

- **Open System Interconnection Model (OSI Model).** *Layers:* 
   - 7) Application
   - 6) Presentation
   - 5) Session
   - 4) Transport
   - 3) Network
   - 2) Data Link
   - 1) Physical 

<p>&nbsp;</p>

- The two main protocols in TCP/IP: **TCP & UDP**
   - ***TCP:*** Slower than UDP because it controls whether the data is reached the other side or not. Uses the “Three-Way Handshake” method.
   - ***UDP:***  It is used in subjects such as audio and video transmission. Faster than TCP but it’s not safe. 

<p>&nbsp;</p>

- **Ports:** computer entrance doors. Each port number is used to distinguish between different simultaneous operations. (ex: generally port 21 FTP TCP File Transfer Control)

<p>&nbsp;</p>

- **ARP (Adress Resolution Protocol):** It is a protocol for mapping an IP address to a physical machine address recognized in the local network.

<p>&nbsp;</p>

- **netdiscover** command

<p>&nbsp;</p>

- **DNS(Domain Name System)**

<p>&nbsp;</p>

- **ping** used to check whether a network is available and if a host is reachable. With this command, we can test if a server is up and running.

<p>&nbsp;</p>

- **Network Services:** DHCP(Dynamic Host Configuration Protocol), NAT(Network Address Translation), VPN(Virtual Private Network)

<p>&nbsp;</p>

- **IP(Internet Protocol):** It is a protocol used by private and public networks to facilitate communication between devices within the network.

  - ***IPv4:*** It is the first version of IP. An IPv4 address has 32-bit addressing space, which means 2^32 = 4.3 billion devices.
  - ***IPv6:*** It is the latest version of IP. IPv6 is used more for the IoT industry due to its more complex nature and a large number of address spaces. The 128-bit IPv6 protocol consists of 8 numbered strings of 4 characters separated by a colon which means an incredible number of supported devices.

<p>&nbsp;</p>

- **arpspoof command:** used to send fake ARP messages to a victim’s machine, tricking it into sending its traffic to the attacker’s machine or another gateway on the network.

<p>&nbsp;</p>

- **Wireshark**

<p>&nbsp;</p>

- **Bettercap:** It is mostly used to manage attacks within the network after it has entered the network.

<p>&nbsp;</p>

- **Bettercap Modules:** net.probe, net.show, arp.spoof, net.sniff, caplets(Ready-made scripts and codes that can be run in bettercap. Used hstshijack caplet)

<p>&nbsp;</p>

- **Google Dorking**

<p>&nbsp;</p>

- **Netcraft** → https://sitereport.netcraft.com/ 

<p>&nbsp;</p>

- **Reverse IP Domain Check** 

<p>&nbsp;</p>

- **.../robots.txt:**  this is a file that tells web browsers to get these sites, not to import these sites.

<p>&nbsp;</p>

- **Web Crawler:** A computer program that automatically and systematically searches web pages for certain keywords.

<p>&nbsp;</p>

- **Subbrute:** free and open-source tool available on GitHub.Used for finding subdomains of the target domain.

<p>&nbsp;</p>

- **msfconsole:** Runs the Metasploit framework's console.

<p>&nbsp;</p>

- **uname -a :** gives us information about the current Linux we are in.

<p>&nbsp;</p>

- **Telnet vs SSH**
  - ***Telnet:*** collects information without encryption that’s why it’s not safe.
  - ***SSH:*** collects information by encrypting it.

<p>&nbsp;</p>

- **Samba:** is the standard Windows interoperability suite of programs for Linux and Unix.

<p>&nbsp;</p>

- **Meterpreter:** This tool gives us the opportunity to interact with other machine.