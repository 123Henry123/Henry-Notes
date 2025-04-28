1. install LDAP by using the command "sudo apt install slapd ldap-utils"
2. use command "sudo dpkg-reconfigure" slapd to set password and other stuff
3. make domain name "something. something else"
4. make  a folder "Ldap_setup" or something
5. inside that folder make a file "start.ldif" must end with ldif.
6. use sudo nano "path to file" to edit the file
7. inside the file put "dn: dc=something, dc=something else"

Workstation
1. to configure settings type "sudo nano /etc/nsswitch.conf" then type "ldap" behind the ones you want enabled.