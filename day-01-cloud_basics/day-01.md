# Day 01 - Cloud Basics

## Objective

Understanding what a server is

## Commands Practiced

* 

## what I did

* Since I do not have an AWS account, I've created a virtual machine(VM) to simulate AWS
* Installed Oracle Virtual Box and created a virtual machine
* Created a linux ubuntu VM and set it up.

## Problems Faced

* Totally confused about how to create and set-up VM.
* When installing Ubuntu on VM, an error occured and the VM's screen went black


## How I fixed

* Followed a tutorial to set up.
* Change graphics setting of the VM, set it to 128 MB

## Key Learnings
* AWS is someone's else Linux machine on the internet, the VM is my Linux machine on my system
* Server: A computer running 24/7
	- The VM is acting as a server here
	- In AWS: EC2 = server
* Storage: Files stored separately from the server
	- In AWS: S3 = storage bucket
* Network: How machines talk to each other
	- In VM: >ip a
	- In AWS: VPC + Security Groups
* SSH: Secure remote login to a server
	- You are physically inside the VM
	- Later in AWS: ssh ubuntu@server-ip
