# Day 06 - Installing software on EC2 (Ubuntu VM)

## Objective

Understanding how to set up a server, remote package installation, updates and sofware setup

## Commands Practiced

* sudo apt update - fetches latest package info
* sudo apt upgrade -y - installs latest versions
* sudo apt install <software
	- sudo apt install <software -y - automatic yes flag

## what I did

* Added second network adapter NAT in VM
* Connected VM to Host through SSH
* Updated VM from host
* Installed nginx and curl in VM from host

## Problems Faced

* Software packages not installing in VM

## How I fixed

* Since host-only-adapter does not allow internet access, I added second network adapter NAT.

## Key Learnings
* Host-only-adapter does not give access to Internet connection
