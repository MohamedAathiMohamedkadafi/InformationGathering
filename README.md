# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1920" height="1020" alt="Screenshot 2026-08-05 160934" src="https://github.com/user-attachments/assets/5b5f7816-6ae4-4bbf-bf63-9bf5d1f63cae" />






## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="1920" height="1080" alt="Screenshot 2026-08-19 225340" src="https://github.com/user-attachments/assets/e3d72169-26b3-46c3-839a-cdfe8e6a2b0b" />



## History of the website:
## output
https://web.archive.org/
<img width="1920" height="1080" alt="Screenshot 2026-08-19 230049" src="https://github.com/user-attachments/assets/3b5d109f-0ae8-43af-88fb-40281a6328c1" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="901" height="976" alt="Screenshot 2026-08-20 100737" src="https://github.com/user-attachments/assets/a2487fa4-4cd9-4190-a5dc-738a1b19bae9" />



## nmap:
###output
<img width="963" height="437" alt="Screenshot 2026-08-20 104820" src="https://github.com/user-attachments/assets/4c1fdfa2-59f5-4ac7-8cf2-b82ea4747f90" />


## Whatweb
### output
<img width="1357" height="907" alt="Screenshot 2026-08-20 110316" src="https://github.com/user-attachments/assets/46820594-a551-4618-81c7-8ccd479352d7" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="802" height="736" alt="Screenshot 2026-08-20 110349" src="https://github.com/user-attachments/assets/6c6a9ac4-2c5f-4e5e-9085-09a0c7b1373e" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="653" height="702" alt="Screenshot 2026-08-20 110920" src="https://github.com/user-attachments/assets/1502eaee-145d-4136-a91a-f92551a9dffc" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
