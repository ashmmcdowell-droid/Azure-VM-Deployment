Using a Virtual Machine on Remote Desktop via Azure (beginner friendly)
This project demonstrates how to deploy a Virtual Machine (VM) on Azure and access it remotely using Remote Desktop Protocol (RDP). The goal is to set up a Windows Server 2022 VM, configure networking, and establish an RDP connection
Technologies Used
•	Environments: Microsoft Azure
•	Operating System: Windows Server 2022
•	Services Used: 
o	Azure Resource Group (vpn-winserv2022)
o	Azure Virtual Machines
o	Remote Desktop Protocol (RDP)
 Deployment Steps
Step 1: Create a Resource Group
1.	Log in to Azure Portal.
2.	Go to Resource Groups → Click "Create" → "Resource Group".
3.	Configure the resource group settings: Image below
4.	Click "Review + Create" → "Create".
 

Creating a Virtual Machine on Azure
5.	Log in to Azure Portal.
6.	Go to Virtual Machines → Click "Create" → "Azure Virtual Machine".
7.	Configure the VM settings:  
o	Resource Group: (vpn-winserv2022)
o	VM Name: vm-WinServ2022
o	Region: Select a data center near your location
o	Image: Windows Server 2022
o	Size: Standard_B2ms (2 vCPUs, 8GB RAM)
o	Administrator Username: Labuser123
o	Password: Set a strong password 
o	Ensure RDP (Port 3389) is selected 
 
9.select inbound port Click "Review + Create" → "Create".


Step 2: Configure Networking for Remote Access
1.	Go to Azure Virtual Machines → Click on your VM.
2.	click on VM then go to the public IP address to the right, select and copy
 
3.	go to your computer search bar and type in Remote Desktop Protocol (RDP).
 
4.	 take the copied IP address and input into Remote Desktop Protocol (RDP).
 
5.	After you hit connect, type in username (Labuser123) and password you created 

6.	and then select yes when the prompt is presented
 
7.	Now you should be successfully connected to the virtual machine.

