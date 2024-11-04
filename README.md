# Wazuh-SIEM-Setup
[Wazuh](https://wazuh.com/) is an open source Security Information Event Manager (SIEM) tool that that can check device vulnerability, check security logs amoung other security configurations. 

## Prerequisites:
The following needs to be downloaded from their respective links.
- [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
- [Ubuntu 22.04 ISO Image](https://releases.ubuntu.com/jammy/)

## Virtual Machine Hardware Requirments: 
This tutorial will only be used for 1 agent. Minimum hardware specification are ment for 1-25 agents. More information can be found on [wazuh](https://documentation.wazuh.com/current/quickstart.html) for multiple agents
- Processor: 4 cores
- Ram: 8GB
- Minimum Storage: 50GB

## Virtual Machine Setup
<p align="center">
Open virtualbox and select "New"
<br />
<br />
<img src="https://i.imgur.com/DjFavqF.png"/>
<br />
<br />

<p align="center">
Name your virtual machine and select your ISO image that was downloaded. Make sure that the "Skip unattended installation" is checked then click next.
<br />
<br />
<img src="https://i.imgur.com/E2GB1WF.png"/>
<br />
<br />

<p align="center">
Set the amount of ram and processor cores as the requirments listed above and click next. (Remember 1024MB is 1GB)<br />
<br />
<img src="https://i.imgur.com/c5x1RXU.png"/>
<br />
<br />

<p align="center">
Set the storage as per the requirments and click next. Add a little more storage to avoid running into issues if your system allows it.<br />
<br />
<img src="https://i.imgur.com/mm3rTyp.png"/>
<br />
<br />

<p align="center">
This page is to confirm your configuration of the VM. Click finish once everything looks good.<br />
<br />
<img src="https://i.imgur.com/4W7102V.png"/>
<br />
<br />

<p align="center">
Select your newly created VM and click "Settings".<br />
<br />
<img src="https://i.imgur.com/IWeMc4u.png"/>
<br />
<br />

<p align="center">
In the "General" section click the advance tab and for "Shared Clipboard" and "DragnDrop" select Bidirectional.<br />
<br />
<img src="https://i.imgur.com/BkEkWz2.png"/>
<br />
<br />

<p align="center">
In the "Display" section make sure the "Video Memory" is maxed out. Also check "Enable 3D Acceleration".<br />
<br />
<img src="https://i.imgur.com/02Ulg7n.png"/>
<br />
<br />

<p align="center">
In the "Network" section under "Adaptor 1" tab and make sure the NAT is selected and enabled.<br />
<br />
<img src="https://i.imgur.com/6ThYFZb.png"/>
<br />
<br />

<p align="center">
Switch to the "Adaptor 2" tab and enable it and make sure the Bridge Adaptor is selected. Click ok to exit.<br />
<br />
<img src="https://i.imgur.com/8tzd9KF.png"/>
<br />
<br />

<p align="center">
Make sure your VM is selected and click start.<br />
<br />
<img src="https://i.imgur.com/Ub4GXRA.png"/>
<br />
<br />

## Installing Ubuntu

<p align="center">
Press enter to install Ubuntu.<br />
<br />
<img src="https://i.imgur.com/6bmHcEz.png"/>
<br />
<br />

<p align="center">
Click "Install Ubuntu".<br />
<br />
<img src="https://i.imgur.com/cvaVeCd.png"/>
<br />
<br />

<p align="center">
Select your own keyboard layout.<br />
<br />
<img src="https://i.imgur.com/tgZmpnt.png"/>
<br />
<br />

<p align="center">
Make sure the "minimal install" and "Download updates while installing Ubuntu" options are checked.<br />
<br />
<img src="https://i.imgur.com/Keq95zc.png"/>
<br />
<br />

<p align="center">
Click install to proceed to the next step.<br />
<br />
<img src="https://i.imgur.com/tonzpXw.png"/>
<br />
<br />

<p align="center">
This warning message may appear. Click continue.<br />
<br />
<img src="https://i.imgur.com/nnqUtre.png"/>
<br />
<br />

<p align="center">
Select your timezone and click continue.<br />
<br />
<img src="https://i.imgur.com/BbebCRP.png"/>
<br />
<br />

<p align="center">
Create a username and password for your machine and select continue.<br />
<br />
<img src="https://i.imgur.com/0kqFMDL.png"/>
<br />
<br />

<p align="center">
This will take a few minutes to install depending on your machine.<br />
<br />
<img src="https://i.imgur.com/6VVurnn.png"/>
<br />
<br />



