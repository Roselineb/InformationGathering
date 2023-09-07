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
# Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
# ![image](https://github.com/Roselineb/InformationGathering/assets/128909895/943aaf10-e5f3-49d0-86d5-df3d4438c5af)
# Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
# ![image](https://github.com/Roselineb/InformationGathering/assets/128909895/1a917cb9-6f65-4c88-a9f4-92d52c3f034c)
# Finding Hosting Company:
get further detail by using ip2location.com website.
## Output:
# ![image](https://github.com/Roselineb/InformationGathering/assets/128909895/ae73ed2f-b6d5-41e6-b992-445230a16e70)
# History of the wbsite:
## Output:
# ![image](https://github.com/Roselineb/InformationGathering/assets/128909895/cb17d694-f90d-4d34-8d5e-46857fe17e3b)
# Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
# ![image](https://github.com/Roselineb/InformationGathering/assets/128909895/eaab21d6-9252-4009-80ba-6932956119bc)
# nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
# ![image](https://github.com/Roselineb/InformationGathering/assets/128909895/b0760d15-52ec-4196-a363-d5e76ab73b35)
## Whatweb:
```
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
```
# Output:
# ![image](https://github.com/Roselineb/InformationGathering/assets/128909895/adc47bbf-59ed-4582-b671-535459e6d352)

 
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
