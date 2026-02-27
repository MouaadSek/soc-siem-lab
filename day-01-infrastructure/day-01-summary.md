\# Day 1 – Wazuh SIEM Deployment



\## Objective

Deploy Wazuh SIEM on Ubuntu Server in VirtualBox.



\## Completed



\- Created Ubuntu Server VM (8 GB RAM, 4 CPU, 80 GB disk)

\- Installed Ubuntu Server 24.04

\- Configured LVM storage

\- Enabled OpenSSH

\- Updated system packages

\- Installed Wazuh SIEM (v4.7.5)

\- Successfully launched Wazuh dashboard



\## Issues encountered



Wazuh installer compatibility warning with Ubuntu 24.04.



Resolved using:



sudo bash wazuh-install.sh -a -i



\## Status



SIEM infrastructure operational.



Next step: Add endpoint and simulate attacks.

