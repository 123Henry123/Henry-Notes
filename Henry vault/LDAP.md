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