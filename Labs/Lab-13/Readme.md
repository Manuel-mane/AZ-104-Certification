# Install NGINX on a Linux VM in Deployment with Cloud Init

## Scenario

My manager asks if I can install NGINX on all new Linux VMs with as little manual intervention as possible. Instead of installing NGINX on each VM manually, I can use
cloud-init to install NGINX during the deployment of a Linux VM.

## Objectives

* Create a New Linux VM
* Deploy VM and Verify NGINX is Installed

## Lab Solution

1.	Create a new Linux VM

![](../../Images/Lab-13/Imagen1.png/)

Leaving everything else as default, I include the cloud_init script in Advanced

![](../../Images/Lab-13/Imagen2.png/)

2.	Deploy VM and Verify NGINX is installed
I go to the deployed VM > Connect > SSH, and copy the command to connect via CLI on Bash

![](../../Images/Lab-13/Imagen3.png/)

Verifying Nginx is working

![](../../Images/Lab-13/Imagen4.png/)
