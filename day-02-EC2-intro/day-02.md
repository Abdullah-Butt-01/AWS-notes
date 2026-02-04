# Day 02 - EC2 instance (simulated using VM)

## Objective

* Understanding what "launching an AWS EC2 instance" means. Here, Vitual Machine = EC2 instance

## Commands Practiced

* hostname - name of the user
* uptime - current time
* df -h
* free -m

## Key Learnings
* EC2: a linux server you rent by the hour. 
* When you launch EC2, AWS does:
	- Chooses hardware
	- Installs Linux
	- Gives it storage
	- Connects it to a network
	- Starts it

	- We have done all of this manually in VirtualBox
* RAM:
	- VM setting: Memory (e.g., 2048 MB)
	- AWS: EC2 instance type (t2.micro, t3.small)
	- More RAM = more cost in AWS
* CPU:
	- VM setting: Processot count
	- AWS: vCPU count
* Disk:
	- VM setting: Virtual Hard Disk
	- AWS: EBS volume
* OS: 
	- VM: Ubuntu ISO
	- AWS: AMI (Amazon Machine Image)
	- Both are Linux images
