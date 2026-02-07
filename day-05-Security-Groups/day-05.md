# Day 05 - Security Groups

## Objective

Understanding how to connect VM to host using SSH

## Commands Practiced

* sudo ufw status - checking firewall status
* sudo ufw enable
* sudo ufw deny ssh
* sudo ufw allow ssh
* sudo ufw relaoad

## what I did

* Enabled Firewall ufw in VM
* Denied ssh in VM and checked from host
* Then, allowd ssh in VM 

## Problems Faced

* 

## How I fixed

* 

## Key Learnings
* Analogy:
	- Server = House
	- Ports = Doors
	- SSH (22) = main door
	- HTTP (80) = guest door
	- Security group = guard at the door
* My SSH connection succeeded because:
	- SSH service was running inside VM
	- Port 22 was reachable
	- VB allowed it
	- if any one fails, SSH fails. AWS works the same way
* sudo ufw deny ssh: This is exactly AWS security group does not allow port 22
* Map this to AWS:
	- EC2: Ubuntu VM
	- Security Group: UFW firewall
	- Port 22: SSH
	- Public IP: VM IP
