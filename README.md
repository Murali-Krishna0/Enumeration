# Developed By
```
Name : MURALI KRISHNA S
REG NO : 212223230129
```
# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

# OUTPUT

![1](https://github.com/user-attachments/assets/533d5dd6-a0da-451f-b03c-fa94625438ea)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

# OUTPUT

![2](https://github.com/user-attachments/assets/c8fc9f5d-4f7e-429c-836a-2cd8063f502f)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

# OUTPUT

![3 before](https://github.com/user-attachments/assets/b0fa67fa-a98f-4662-912f-f1d100e25d66)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

# OUTPUT

![3](https://github.com/user-attachments/assets/38bc58b8-88e8-476e-b2e0-9dbbccc11b1f)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

# OUTPUT

![4](https://github.com/user-attachments/assets/ba21158a-9b96-463b-896d-7008ff5c557f)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

# OUTPUT

![5](https://github.com/user-attachments/assets/01b26da4-1c5d-4ba0-b813-c4d0e717d530)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:

![7 1](https://github.com/user-attachments/assets/013953be-7c78-4498-806b-eec84957443b)

![8](https://github.com/user-attachments/assets/c28c9983-3204-43a3-8d00-8ba59a208ba3)





##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

# OUTPUT

![9](https://github.com/user-attachments/assets/4d185538-aeb0-4f4e-95fe-2b6f02c46fd3)

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 # Output
  
![10](https://github.com/user-attachments/assets/6e3b6687-20fb-42d7-b8e9-f31fd46f4464)

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

# OUTPUT

![428126899-6181cd5f-f835-48f1-845a-7a45a7c655af](https://github.com/user-attachments/assets/d8f0613b-f2d7-4c9e-8a12-c279caaa193e)

select any username in the first column of the above file and check the same

# OUTPUT

![11](https://github.com/user-attachments/assets/45343bba-49f3-4efa-84b6-5e1f14105659)

# Telnet for smtp enumeration

Telnet allows to connect to remote host based on the port no. For smtp port no is 25 telnet 25 to connect and issue appropriate commands

# OUTPUT

![12](https://github.com/user-attachments/assets/467bd50e-fd84-4173-b290-f8fc7363a7d6)

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

![13](https://github.com/user-attachments/assets/2cbd57b1-4138-4c2c-b930-36a026dd50ad)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

