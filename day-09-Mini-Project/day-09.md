# Day 09 - Mini Project

## Objective

Simulated EC2 Server Deployment

## Commands Practiced

* sudo lsof -i :80 - Check who owns the Port 80

## what I did

* Installed apache on simulated EC2 (Ubuntu VM)
* Deployed custom webpage
* Verified server running
* Located apache logs
* Stored apache logs in simulated S3 bucket

## Problems Faced

* Enabling Apache, Error was occuring

## How I fixed

* Stopped the nginx process and apache worked

## Key Learnings
* Services compete for system resources, always check who is using a port
* localhost is always the machine you are currently on, ssh does not give localhost.
	- Use VM IP ti access the VM services from host
