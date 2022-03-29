# Add, Remove and Update Tags for Resources in Azure

## Scenario
The finance department has reached out to you, requesting additional taxonomy information on a recent Azure bill, including who created the resources, which department budget should be used for the resources and if the resources are necessary for running business ciritcal systems. If there are any non-essential business systems, they ask that you signify that in some way.

## Learning Objectives

* Add Tags to the Resource Group
* Remove Tags for VM and Mark for Deletion
* Change Tags for the Virtual Network


## Lab Solution

For this lab, I will manily use Azure CLI. 

* First, I open PowerShell in Azure and create a storage to be able to use it

![](../../Images/Lab-1/Imagen1.png/)

1.	Add Tags to the Resource Group.
   
   - Listing the resources groups
     
![](../../Images/Lab-1/Imagen2.png/)

   - Adding the Tags
    
![](../../Images/Lab-1/Imagen3.png/)

**Using PowerShell:**

  -  Retrieving the Resource info and setting the tags variable

![](../../Images/Lab-1/Imagen4.png/)
 
 - Adding the tag to the resource group

![](../../Images/Lab-1/Imagen5.png/)
![](../../Images/Lab-1/Imagen6.png/)

2.	Remove Tags from VM and Mark for Deletion

 - Showing VMs tags

![](../../Images/Lab-1/Imagen7.png/)

- Remove tags from VM

![](../../Images/Lab-1/Imagen8.png/)

- Set Mark for Deletion tag

![](../../Images/Lab-1/Imagen9.png/)

3.	Change the Tags for the Virtual Network

-	Listing Virtual networks:

![](../../Images/Lab-1/Imagen10.png/)

- Adding Tags to the Virtual Network

![](../../Images/Lab-1/Imagen11.png/)
