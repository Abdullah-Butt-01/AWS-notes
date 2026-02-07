# Day 04 - SSH connecting VM to Host

## Objective

Understanding how to connect VM to host using SSH

## Commands Practiced

* ssh username-VM@ip
* ip a

## what I did

* Changed VM's network setting to Host-only Adapter
* Got the IP using 'ip a'
* Connected VM to host

## Problems Faced

* Using 'ip a', IP of VM (192.168.****) not showing

## How I fixed

* Changed network setting of VM from 'NAT' to 'Host-only adapter'

## Key Learnings
* SSH: Secure remote terminal access
	- Here; AWS EC2 = VM
* EC2 already has installed SSH, in VM, we are doing it manually
