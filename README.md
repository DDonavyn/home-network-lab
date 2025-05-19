# Cisco Router Lab – Personal Networking Project

I created this lab to build hands-on experience with real Cisco hardware after not landing a summer internship. It includes basic configuration, SSH access, ACLs, and connectivity between a Linux PC, Cisco router, and switch.

## Folder Structure

- `configs/` – Contains raw configuration files from the router and switch
- `screenshots/` – Holds screenshots of CLI output, ping tests, and setup verification
- `docs/` – Project documentation and notes (this file)

## What I Configured

- Console access to a Cisco 1921 router using Tera Term
- IOS recovery using ROMMON and `confreg 0x2142`
- Hostname, enable secret, and local user account
- IP address assignment to interfaces
- SSH remote access with RSA keys and login security
- Extended ACL to allow ICMP, SSH, and HTTPS, block all else
- Ping verification from Linux PC to router and switch
- Saved and documented full running configuration
-Configured VLAN and applied IP and subnet to VLAN1
-Configure and apply a basic inbound firewall on the router's LAN interface using an extended ACL to allow only specific traffic types and deny all else.

## Roadmap (Coming Next)

- Complete StrongSwan VPN tunnel from Linux to router
- Set up syslog logging for ACL hit tracking
- Add inter-VLAN routing and simulate DMZ setups
- Automate config backups to local storage or SCP

## Screenshots

Screenshots will be in the `/screenshots` folder to show:
- `show running-config`
- Ping results through linux
- Interface configuration
-Firewall results

