1. install LDAP by using the command "sudo apt install slapd ldap-utils"
2. use command "sudo dpkg-reconfigure" slapd to set password and other stuff
3. make domain name "something. something else"
4. make  a folder "Ldap_setup" or something
5. inside that folder make a file "start.ldif" must end with ldif.
6. use sudo nano "path to file" to edit the file
7. inside the file put 
dn: uid=username,dc=part of domain infront of the dot,dc=part of domain after the dot
objectClass: inetOrgPerson
objectClass: posixAccount
uid: username
cn: full name
sn: last name
uidNumber: unique number for each user
gidNumber: group number
homeDirectory: /home/username
loginShell: /bin/bash
gecos: "full name, birthday, age, pronouns"
userPassword: hashed password using "slappasswd"
8. save the file and exit
9. run ldapadd -x -D "cn=admin,dc=part of domain before the dot,dc=part of domain after the dot" -w ldap password -f name of file
10. or run my script

Workstation
1. to configure settings type "sudo nano /etc/nsswitch.conf" then type "ldap" behind the ones you want enabled.
2. go to sudo nano /etc/nslcd.conf and change the link and passwords and stuff
3. go to sudo nano /etc/ldap/ldap.conf and change the link
4. find the ip address of the server with ip addr show
5. in the workstation go to sudo nano /etc/hosts and put the ip hit tab and put the name of the domain.
6. run ping name of the domain to check if you did it right.
7. run sudo getent passwd username of one of the people you added on the server
8. if it returns something that means they're connected

Documented process for marking users inactive so they can no longer log in. 
Check the last time to user has logged in. If the user hasn't logged in in a designated amount of days remove then from the server.

My experience:
While making a ldap server i faced lots of difficulties and struggles. When I first initialized the ldap server I wasn't familiar with the ldap commands. After a while I got the hang of it and  configured the domain name and added the users.

Later I went onto the workstation and started configuring it. At first I didn't know what to configure. After digging deep I found out what I needed to download and how to configure them.

Next I moved on to creating scripts. I haven't had much experience in ldap so I struggled a but at the start. When I wanted to do something but I didn't know the command I would ask chatgpt for assistance. After lots of trial and error I managed to get my script to work. However, I forgot to delete the previous users I had created which resulted in overlapping uid numbers. I spent a few days trying to figure out what was wrong and eventually I found out what went wrong.

Pros: It's lightweight so it doesn't take up too much storage.  It is very secure and hashes user passwords. It makes it easy to search for specific users and groups. Can store all sorts of user data that some servers can't store.
