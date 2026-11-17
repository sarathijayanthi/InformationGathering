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

<img width="1366" height="643" alt="par 1ss" src="https://github.com/user-attachments/assets/4120415c-c46e-4577-b3b6-fd1627ea550c" />





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

<img width="1366" height="643" alt="parchatgpt_ss" src="https://github.com/user-attachments/assets/fa82c697-2605-47d8-b898-89aebd6844b0" />




## nmap:
```
nmap -sL chatgpt.com
```

### Output

<img width="1366" height="643" alt="chatgpt2" src="https://github.com/user-attachments/assets/f7ff5283-2778-4498-8860-1735e3649a0d" />



## Whatweb:
```
whatweb https://chatgpt.com
```

### output

8t<img width="1366" height="643" alt="wahtweb_ss" src="https://github.com/user-attachments/assets/6e9025bf-092c-4dd0-8d10-7c70274b7487" />



## httprint:
```
httprint -h 127.0.0.1 -s /usr/share/httprint/signatures.txt -P0 -t 30000
```


### output

<img width="1366" height="643" alt="httprint" src="https://github.com/user-attachments/assets/dcae6368-41ba-4c8e-99ef-5a20c849069b" />




# Tracing the Location

TCP Traceroute:

sudo traceroute -T www.google.com

### output

<img width="1366" height="643" alt="trace" src="https://github.com/user-attachments/assets/b818146d-b145-49ce-ba6c-98df143d48bc" />



## UDP Traceroute:

sudo traceroute -U www.google.com

## output

<img width="1366" height="643" alt="trace_route" src="https://github.com/user-attachments/assets/77b7b54f-9149-42e8-85cf-2d7a256c3c74" />




## ICMP Traceroute:

sudo traceroute  www.google.com

## output

<img width="1366" height="643" alt="icmptraceroute" src="https://github.com/user-attachments/assets/2cf54450-1259-40bb-b088-877b95b54740" />







## RESULT:
The information gathering techniques tools/procedure were  identified successfully
