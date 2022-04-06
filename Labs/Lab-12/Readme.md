# Using PowerShell to Resize an Azure Virtual Machine in an Availability Set

## Scenario

My company's finance department explains that the cost of Azure virtual machines (VMs) is over budget. I must find an easy solution to decrease the cost of Azure VMs 
in my subscription. Using only PowerShell, I have to identify the VMs with low CPU utilization and change their size.

## Learning Objectives

* Start Cloud Shell
* Get the VM Size and CPU Metrics
* Resize VMs in Availability Set

## Lab Solution

1.	Start Cloud Shell
I go to the command icon on the top, select Power Shell > Advanced Settings, and create an unique storage account and file share as follow:

![](../../Images/Lab-12/Imagen1.png/)

2.	Get the VM Size and CPU Metrics
Finding the size of the VMs

![](../../Images/Lab-12/Imagen2.png/)

Getting the VM Subscription name

![](../../Images/Lab-12/Imagen3.png/)

Getting the VM CPU metrics

![](../../Images/Lab-12/Imagen4.png/)

3.	Resizing the VMs in the Availability Set
Checking which VMs are available to resize within the VM hardware cluster 

![](../../Images/Lab-12/Imagen5.png/)

PowerShell command to resize the VM

![](../../Images/Lab-12/Imagen6.png/)

Verifying the VM was updated

![](../../Images/Lab-12/Imagen7.png/)
