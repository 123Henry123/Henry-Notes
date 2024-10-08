# Henry Notes
Grade 10 Cybersecurity


INDEX
Logic gates
Basic Linux Commands
Computer Parts
Networking
Permissions
Useful Commands
Keywords/Abbreviations
Git



LOGIC GATES\Boolean
IS	NOT	AND	OR
input	output
0	false
1	true

A	B	AND	OR	XAND	NOR
0	1	F	T	F	F
1	0	F	T	F	F
0	0	F	F	T	T
1	1	T	T	T	F
XAND (Exclusive AND) only if both are equal.
NOR (Neither this nor that) only proves things that are false.


Basic Linux Commands:

henry@Henry:~$
henry = user
Henry = PC name
~ = home/henry
cd / = goes to root directory
ls = list
cd = change directory
cd- = go back
pwd = prints current wording directory
mkdir/rmdir = make/remove directory
cat = view what’s in a file
touch = creates empty documents
nano file_name = allows you to edit a file
mv = rename
find = search for files
Rm = remove stuff

Computer Parts
Applications:
OS (Operating System): manages all the software and hardware on the computer.
File systems:  a set of data structures, interfaces, abstractions, and APIs that work together to manage any type of file on any type of storage device, in a consistent manner.
Computer:	Shell: The shell manages the interaction between you and the operating system by prompting you for input
Kernal: acts as a bridge between applications and data processing performed at hardware level using inter-process communication and system calls.
		Hardware: store and run the written instructions provided by the software
Hardware: 	Motherboard, CPU(Central Processing Unit), GPU(Graphics Processing Unit/Graphics Card), SSD(Solid State Drive), RAM(Random Access Memory), Case, Cooler, Power supply.



Networking
1. IP Address (Internet protocol): The number used to identify devices that are connected to the internet.
2. Subnet mask: It hosts portions in an IP address for routing and identification.
3. Gateway: It connects network devices, helping them communicate easier.
4. DNS (Domain Name System): (only 13 DNS servers in the world) Copies URL with IP address.
5. Network switch: It is a device that connects local networks allowing them to communicate.
6. Network Router: A network router is a device that connects networks 	and directs data traffic.
7. Access point: is allows wifi enabled devices to connect to a wired network.
8. MAC address: Identifier assigned to a network interface for communication.
9. Port: Allows multiple devices to use networks without interference.
10. Types of networks (Wan, LAN, PAN MAN and VPN)

Permissions
ls -l = view permissions
r = read = 4
w = write = 2
x = execute = 1
types of people it affects
User/owner = u
Group = g
ALL = o
+ to add user to file
- to remove permissions
= to set exact permissions
Chmod = Change file permissions


Useful Commands
1. Ifconfig (internet configuration) = It is used in Unix-like operating systems like Linux, to configure and display information about network interfaces on a system.
2. ip (internet protocol) = it is the address of your device. You would 	use it to view information about network interfaces, like their name, states, and hardware addresses. It also replaced the ifconfig and route command.
3. host = used to find the ip address of a specific domain name or find the domain name of an IP address.
4. tracepath = traces network paths and is similar to traceroute.
5. ss = used to display socket statistics. It replaced netstat.
6. dig = retrieves information about various DNS.
7. iwconfig = It configures wireless network interfaces on linux systems.
8. hostname = It shows the name of the device you’re using.
9. ping = it shows how well your computer is working.
10. ifplugstatus = You need to download ifplugd to use the command. The command checks the link status of a network interface.
11. tcpdump = Good for network troubleshooting, analysis, debugging.
12. wget = used to download files from the internet
13. iftop = view a list of network connections in real time and their transfer ratesGrade 10 Cybersecurity


INDEX
Logic gates
Basic Linux Commands
Computer Parts
Networking
Permissions
Useful Commands
Keywords/Abbreviations
Git



LOGIC GATES\Boolean
IS	NOT	AND	OR
input	output
0	false
1	true

A	B	AND	OR	XAND	NOR
0	1	F	T	F	F
1	0	F	T	F	F
0	0	F	F	T	T
1	1	T	T	T	F
XAND (Exclusive AND) only if both are equal.
NOR (Neither this nor that) only proves things that are false.


Basic Linux Commands:

henry@Henry:~$
henry = user
Henry = PC name
~ = home/henry
cd / = goes to root directory
ls = list
cd = change directory
cd- = go back
pwd = prints current wording directory
mkdir/rmdir = make/remove directory
cat = view what’s in a file
touch = creates empty documents
nano file_name = allows you to edit a file
mv = rename
find = search for files
Rm = remove stuff

Computer Parts
Applications:
OS (Operating System): manages all the software and hardware on the computer.
File systems:  a set of data structures, interfaces, abstractions, and APIs that work together to manage any type of file on any type of storage device, in a consistent manner.
Computer:	Shell: The shell manages the interaction between you and the operating system by prompting you for input
Kernal: acts as a bridge between applications and data processing performed at hardware level using inter-process communication and system calls.
		Hardware: store and run the written instructions provided by the software
Hardware: 	Motherboard, CPU(Central Processing Unit), GPU(Graphics Processing Unit/Graphics Card), SSD(Solid State Drive), RAM(Random Access Memory), Case, Cooler, Power supply.



Networking
1. IP Address (Internet protocol): The number used to identify devices that are connected to the internet.
2. Subnet mask: It hosts portions in an IP address for routing and identification.
3. Gateway: It connects network devices, helping them communicate easier.
4. DNS (Domain Name System): (only 13 DNS servers in the world) Copies URL with IP address.
5. Network switch: It is a device that connects local networks allowing them to communicate.
6. Network Router: A network router is a device that connects networks 	and directs data traffic.
7. Access point: is allows wifi enabled devices to connect to a wired network.
8. MAC address: Identifier assigned to a network interface for communication.
9. Port: Allows multiple devices to use networks without interference.
10. Types of networks (Wan, LAN, PAN MAN and VPN)

Permissions
ls -l = view permissions
r = read = 4
w = write = 2
x = execute = 1
types of people it affects
User/owner = u
Group = g
ALL = o
+ to add user to file
- to remove permissions
= to set exact permissions
Chmod = Change file permissions


Useful Commands
1. Ifconfig (internet configuration) = It is used in Unix-like operating systems like Linux, to configure and display information about network interfaces on a system.
2. ip (internet protocol) = it is the address of your device. You would 	use it to view information about network interfaces, like their name, states, and hardware addresses. It also replaced the ifconfig and route command.
3. host = used to find the ip address of a specific domain name or find the domain name of an IP address.
4. tracepath = traces network paths and is similar to traceroute.
5. ss = used to display socket statistics. It replaced netstat.
6. dig = retrieves information about various DNS.
7. iwconfig = It configures wireless network interfaces on linux systems.
8. hostname = It shows the name of the device you’re using.
9. ping = it shows how well your computer is working.
10. ifplugstatus = You need to download ifplugd to use the command. The command checks the link status of a network interface.
11. tcpdump = Good for network troubleshooting, analysis, debugging.
12. wget = used to download files from the internet
13. iftop = view a list of network connections in real time and their transfer rates
14. arp = Used to display and modify the Address resoulution protocol (APR) cache on a system. APR is a network protocol used to map an IP address to a physical (MAC) address on a local network.
15. Traceroute = it traces network paths.
16. netstat = Provides information about network connections, routing tables, interface statistics, and other network-related information on a computer.
17. nslookup = query DNS servers to obtain domain name or IP address mapping, or other DNS records
18. mtr = It combines "traceroute" and "ping" commands. It sends packets it you destination then it continuously updates the information.
19. route = It is used to display or manipulate the routing table. The routing table is a set of rules that dictates how network traffic should be directed in a computer network.
20. whois = It queries the WHOIS database. The WHOIS database contains information about registered domain names, IP address allocations and other registration details.
21. IRC (internet relay chat): It is a protocol used for real-time text messaging or chat using the internet. It allows people to communicate through private chats or groups.

Keywords/Abbreviations
IP adress = Internet Protocol
GUI = Graphic User Interface
DNS = Domain Name System
OS (Operating System): manages all the software and hardware on the computer.


Git
Git init = make repository
Git add filename = adds file so you can commit later

git commit = save progress
git checkout -b “branch name” = make branch
git checkout “branch name” = switch to branch
git restore “file name” = revert to last commitment version
git rm –cached “file name” = remove file from repository
git reset --soft HEAD~x = remove x commits









 Passwords
bot_1 = Viscount2022

14. arp = Used to display and modify the Address resoulution protocol (APR) cache on a system. APR is a network protocol used to map an IP address to a physical (MAC) address on a local network.
15. Traceroute = it traces network paths.
16. netstat = Provides information about network connections, routing tables, interface statistics, and other network-related information on a computer.
17. nslookup = query DNS servers to obtain domain name or IP address mapping, or other DNS records
18. mtr = It combines "traceroute" and "ping" commands. It sends packets it you destination then it continuously updates the information.
19. route = It is used to display or manipulate the routing table. The routing table is a set of rules that dictates how network traffic should be directed in a computer network.
20. whois = It queries the WHOIS database. The WHOIS database contains information about registered domain names, IP address allocations and other registration details.
21. IRC (internet relay chat): It is a protocol used for real-time text messaging or chat using the internet. It allows people to communicate through private chats or groups.

Keywords/Abbreviations
IP adress = Internet Protocol
GUI = Graphic User Interface
DNS = Domain Name System
OS (Operating System): manages all the software and hardware on the computer.


Git
Git init = make repository
Git add filename = adds file so you can commit later

git commit = save progress
git checkout -b “branch name” = make branch
git checkout “branch name” = switch to branch
git restore “file name” = revert to last commitment version
git rm –cached “file name” = remove file from repository
git reset --soft HEAD~x = remove x commits









 Passwords
bot_1 = Viscount2022
