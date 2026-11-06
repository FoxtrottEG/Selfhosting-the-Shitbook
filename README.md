# Selfhosting-the-Shitbook
Self hosted Backup and synchronization solution for Images,Notes and Documents

## Prerequisites

### Hardware Requirements
min. 2gb ram, recommended 4gb  
CPU with min 2 cores at 1.6 GHz  
Storage minimum 20gb recommended 100  
recommended as Immich requires a decent amount of storage due to it being a Image and video hosting service

### Other Requirements
- An internet connection  
- A Tail-scale account


## Hardware and Software
For this Project I am using a modified T1 Macbook<br/> 
The Macbook had its GPU shutoff for lower power Usage and its battery removed to negate the risk of a fire hazard<br/>
If you wish to use a T1 Macbook or similar Laptops I recommend you complete the aforementioned modifications using IFixIt documentation before spinning up containers<br/>
```
The GPU deactivation script will be included in the repo
```
Another recommendation for headless laptops is to purchase an external LAN dongle for a wired connection

### The Installed software packages include
- DHCPD - SystemD service that automatically assigns a local IP adress to the device using the DynamicHostConfigurationProtocol
- openSSH - Open source ssh service for remotely connecting to the machine  
- Tailscale - 0 trust VPN service  
- Docker  
- Docker-Compose  

### Recommendations
- cfdisk  
- chrontab  
- btop

### Chosen Docker Containers

- Immich - Immich is a self hosted photo and video management solution with ML capabilities for facial recognition
- Paperless - document backup
- CouchDB - CouchDB will be used to self-host a backup solution for the Note taking application Obsidian
- Glance - Server Management Dashboard
- Reactive resume

## Installation 
### Installation of the chosen operating distribution



### Setting up TailScale

### Setting up Docker

### Setting up Docker containers

Obsidian sync
https://dev.to/lightningdev123/how-to-set-up-a-self-hosted-obsidian-sync-server-hcn

### patching Vulnerability in  Immich Maschine Learning

## Optional Automation 
