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

<img width="1881" height="867" alt="image" src="https://github.com/user-attachments/assets/db008877-6676-42fd-92b3-da83df00c001" />


## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## output

<img width="1366" height="643" alt="par 1ss" src="https://github.com/user-attachments/assets/b28a4332-6eb8-443d-bcdc-3c6176479579" />



## Finding Hosting Company

get further detail by using ip2location.com website.
## output

<img width="1895" height="855" alt="image" src="https://github.com/user-attachments/assets/46f22c3a-e734-47cb-ba65-6ebc87297bd3" />




## History of the website:

## output
https://web.archive.org/

<img width="1891" height="855" alt="image" src="https://github.com/user-attachments/assets/f2f1872c-7a17-4a50-b8bf-71d8583d6bca" />


# Webserver Fingerprinting:

## Netcat:
```sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
```

### Output

<img width="1366" height="643" alt="parchatgpt_ss" src="https://github.com/user-attachments/assets/8b26ea4b-e1e5-4c57-9cb2-25c7600f2897" />

## nmap:
```
nmap -sL chatgpt.com
```

### Output
<img width="1366" height="643" alt="chatgpt2" src="https://github.com/user-attachments/assets/28fe5bb7-6886-4123-84e1-70c199ee393c" />



## Whatweb:
```
whatweb https://chatgpt.com
```

### output

<img width="1366" height="643" alt="wahtweb_ss" src="https://github.com/user-attachments/assets/516186e0-eeb6-4f27-890e-3eea31fbce03" />


## httprint:
```
httprint -h 127.0.0.1 -s /usr/share/httprint/signatures.txt -P0 -t 30000
```


### output

<img width="1366" height="643" alt="httprint" src="https://github.com/user-attachments/assets/3617686c-6f70-4643-824f-20926587af0a" />


TCP Traceroute:

sudo traceroute -T www.google.com

### output

<img width="1366" height="643" alt="trace" src="https://github.com/user-attachments/assets/bad0e680-857e-4940-9051-a0489e1b7aab" />

## UDP Traceroute:

sudo traceroute -U www.google.com

## output

<img width="1366" height="643" alt="trace_route" src="https://github.com/user-attachments/assets/812f0a0c-e1c3-4a60-ab4f-516ca993eda3" />




## ICMP Traceroute:

sudo traceroute  www.google.com

## output

<img width="1366" height="643" alt="icmptraceroute" src="https://github.com/user-attachments/assets/f3660010-cdf7-4fcc-9a88-4826fa5c6d7b" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
