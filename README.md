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
![image](https://github.com/user-attachments/assets/d74c266f-77b4-4750-b8e7-247c03bfdff7)

## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![image](https://github.com/user-attachments/assets/2418e1a1-e048-4a4d-912d-6d549c88fbc7)

## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![image](https://github.com/user-attachments/assets/27905055-b565-4ce2-99bf-df2086dc4e7a)

## History of the wbsite:
## Output:
https://web.archive.org/
![image](https://github.com/user-attachments/assets/11e9378a-95d8-4f02-8d85-989337dee549)

## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![image](https://github.com/user-attachments/assets/e6a33d9d-eb77-4c37-b940-9d3b5cee383a)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/user-attachments/assets/99c114a8-66bc-4b38-b7b4-22a4192fce3a)

## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![image](https://github.com/user-attachments/assets/b7d42ba6-7d84-44b8-93fa-055ff9205bb6)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/user-attachments/assets/86930db7-dc55-4952-a257-8445d31295b3)

## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/user-attachments/assets/34f03b57-0ddd-422e-82ef-7348a8e5ca15)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/user-attachments/assets/8f3d0959-5fb2-47e3-9750-d92a3b0290cd)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/user-attachments/assets/9e869b07-c964-4472-a755-4ab77c69656d)






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
