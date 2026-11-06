### Selfhosting-the-Shitbook
Self hosted Backup and synchronization solution for Images,Notes and CVs

## Prerequisites

# Computer with 
min. 2gb ram, recommended 4gb <br/>
CPU with min 2 cores at 1.6 GHz <br/>
Storage minimum 20gb recommended 100<br/>
recommended as Immich requires a decent amount of storage due to it being a Image and video hosting service

An internet connection
A Tail-scale account


## Hardware and Software
For this Project I am using a modified T1 Macbook 
The Macbook had its GPU shutoff for lower power Usage and its battery removed to negate the risk of a fire hazard
If you wish to use a T1 Macbook or similar Laptops I recommend you complete the aforementioned modifications using IFixIt documentation before spinning up containers
The GPU deactivation script will be included in the repo

Another recommendation for headless laptops is to purchase an external LAN dongle for a wired connection

# The Installed software packages include
DHCPD - SystemD service that automatically assigns a local IP adress to the device using the DynamicHostConfigurationProtocol 
openSSH - Open source ssh service for remotely connecting to the machine
Tailscale - 0 trust VPN service 
Docker 
Docker-Compose

recommendations
cfdisk
chrontab
btop

## Installation 
# Installation of the chosen operating distribution

# Setting up TailScale

# Setting up Docker

# Setting up Docker containers

# patching Vulnerability in  Immich Maschine Learning

## Optional Automation 
