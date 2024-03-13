# cy-malware-intro-
# Lab Title: 	INTRO TO NETWORK SECURITY

## Date: 03/10/2024

## Lab Overview:

In this lab we explored Fierwalls in Windows and Linux setting, we did some con figurations and added some rules.

---

### Part #? - Network Security - Firewalls

#### Time for Lab Completion:

1 hr 30 min

#### Purpose of the Lab:

In this lab we explored Fierwalls in Windows and Linux setting, we did some con figurations and added some rules.I got to enable the firewall on the windows app and viewwd its fetures, and configured setting with on control panel and WFAS. On the Linux i enabled the firewall and created some rules for it to follow. 

#### What did you enjoy about the lab?

Great refresher on Firewalls both on windows and linuxs. Did not know Linux firewall does not start up automaticly like windows does and you have to set outbounf=d and inbound traffic rules right away.

#### What did you find most challenging about the lab?

Pretty easy to follow and keep up.

Describe a host-based firewall. 
Is a firewall that is not installed onto the network its self but on the computer and definde agighnts malware traffic that got throught the network firewall.
Describe a network-based firewall.
oppisite from host based firewall, network base is a firewall that is between the internal and external networks and inspects oncoming traffic coming in.
Which type of firewall is Windows Firewall?
Host-base
Explain the Notification state in Windows Firewall.
In the notification state there are 3 ON, OFF, and or BLOCK, you can have the firewall on and block all connnection or just have it complete off.
Discuss why network profiles are important.
Describe the three types of profiles found in the Windows Firewall.
Explain and give an example of network locations.
Profiles are important because each has its own set of rules and determine firewall rules. There are Public, private and domain profiles. Each are defind by their set of rules and their location, public is a network that is outside ones home and isnt trusted and might have stricter rules as where private is a host home network where you can have loose rules. Domain os being connected to a domaina nd the rules are set by the network admin.
n Windows Firewall, what do the Home/Work (Private) and Public columns indicate?
Where you set the rules, like if you on our home trusted network and you know the devices on the network then you check on private  not public, since thats an unknow area and devices.
Define the term: firewall rule (exception).
This is when you want to exclude a rule to a certin profile, like when you are a priavte network then you will allow certain traffic go throught but not on public host.
Explain why it is a risk to allow programs and add exceptions through the firewall.
It can leave your network open to attackers and malware
Explain why isn’t it necessary to create an inbound rule on the Internal 192.168.12.10 Windows Server so that it can receive the response (ICMP echo reply) from the Internal 192.168.12.11 Windows Server.
There is a rule set that permits communiction on both servers because they both on same network.
Identify the four basic types of firewall rules.
Allow/allow specific and deny/deny specific
Compare the ufw status verbose command output with Windows Firewall with the Advanced Security Windows Firewall Properties you investigated in an earlier lab. Describe the major similarities that you observe.
Its little more complex when you getinto more and different ruls and statis, but you are basicly setting the same rules and pinging each connection.
Explain the advantages and disadvantages of having the firewall disabled at start up in the Linux operating system.
You get to start it up yourself and set the rules that you want all at once.
Create and document two firewall rules that you think would be important to include if all outbound traffic is being denied by the firewall rules. Explain your decision.

---

### Part #? - Network Troubleshooting

#### Time for Lab Completion:

45 min

#### Purpose of the Lab:

Trouble shoot some comon network issues and learn to troubleshoot and fix problems. The network needs to be able to run smoothly and not be vulnable to attacks, so running some scans and fixing each proble with great investigation wiil keep it running smoothly.

#### What did you enjoy about the lab?

Great troubleshooting laab, nice to work with comand promp and run some test.

#### What did you find most challenging about the lab?

Easy run throught not difficult at all.

What does the nslookup command do?
Test and troubleshoots the DNS servers and shows available commands
What utility can be used to find out the IP address, subnet mask, and default gateway configured on a computer?
ipconfig /all
What is the function of the DNS protocol?
Its a way for use to find websites with hostnames insted of #s
If a client does not have the correct DNS server address specified in its TCP/IP properties, what will occur?
You will be lead to and website that hasnt been created or doesnt excist.
What IPv4 address was assigned to the Internal 192.168.12.11 Windows Server by the DHCP server?
192.168.12.15
Could this machine have leased a different IP address?
yes
According the DHCP server configurations, what range of IP addresses could this machine been assigned by DHCP?
24
After configuring the host as a DHCP client, were DHCP and DNS server addresses dynamically allocated correctly?
yes
What is the function of the ipconfig/release and the ipconfig/renew commands?
They are used to release the assigned ip address and the give it a new one
What type of devices would be better served to have static IP configuration?
Any device out the network like printers, routers and phones
