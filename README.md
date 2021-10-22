# Honey Pot Analysis

## Table of Content
- Introduction
- Overview
- Information About the Attacker
- Information About the Attack
- Conclusion 


# Introduction
This is my analysis of a honeypot I setup using T-Pot and AWS.I am using AWS to host my server
and T-POT to create the honeypot.

## T-POT 
This tool contains multiple honey pot and was developed by T-Mobile.
I hosted the honeypots on a AWS EC2 instance.This tool not only gives you multiple pre-built honeypots but as 
well as tools for you to understand what the attacker did while he was on your server.I hosted my server 
in the Oregon region

## Cowrie
Cowrie is one of the many honeypots that T-Pot offers.I will be making my analysis on this.
This honeypot is used to log SSH bruteforce attacks
as well as the command the hackers run after gaining access to my server.

# Overview

## Attacks
After my server went live for around 3 hours there have been more than 100 attacks already.

![](Screenshot_2021-10-21_12-43-22.png)

## Attacker IP
These are the IP address of attackers that created the most amount of traffic

![](ip_addr.png)

## Companies
Most if not all of these attackers used a company that offered a VPS or a web-hosting service to conduct their
attacks.These are the companies they used.

![](Screenshot_2021-10-21_12-45-00.png)

## Commands
These are the commands the attackers ran once they got access to the server

![](command.png)

# Information about the attacker 

## IP Address 141.98.10.60
### Virus Total
The results after running the IP address in virustotal

![](141scan.png)

### Geolocation
This IP address is under a web-hosting Company called UAB Host Baltic.It is located in Lituania.

![](lithuania.png)

### Credential
The attacker gain access to my server by a brute force SSH attack.These are the usernames and password he used.
Username
![](141user.png)

Password
![](141pass.png)

### Command
These are the commands he ran after gaining access.
![](141commands.png)
The attacker only ran 3 commands in total.The commands were also the same.Hive is a OS primiarly used 


## IP Address 167.88.161.219
### Virus Total
The results after running the IP address in virustotal 
![](167scan.png)















