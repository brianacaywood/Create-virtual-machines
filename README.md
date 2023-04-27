# Create-virtual-machines
Create subscriptions, resource groups, subnet mask, virtual machines (VMs)
<p align="center">
<img src="https://cdn.freebiesupply.com/logos/thumbs/2x/microsoft-azure-2-logo.png" alt="Virtual Machine Creation"/>
</p>

<h1>Create subscriptions, resource groups, subnet masks, and virtual machines using Azure </h1>
In this tutorial, we observe how we create subscriptions and observe how resource groups and subnet masks are created when virtual machines are created using Microsoft Azure <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Windows Remote Desktop
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Actions and Observations</h2>

<p>
<img src="https://user-images.githubusercontent.com/131008349/232944197-50f5317d-7e4c-49e6-8be4-e5683e7d0bf0.PNG" height="80%" width="80%" alt="Create subscription in Azure"/>
</p>
<p>
Create username and password then login to Portal.Azure.com to create subscription for your resource groups, subnet mask, and virtual machine (VM) to be housed under. 
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/232949762-83ed0ae5-b306-4f01-b665-7917e159c7eb.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Search "Resource Groups" in Azure to locate then create new resource group to house all units under the same project by naming it something related to the project and selecting the region you want your elements to live. Make sure the region for your resource group and VM match. This step can also be done by going directly to the "Virtual Machines" tab, creating a new VM, and then selecting "create new".
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/232951715-d799320b-7195-406b-8726-1ee3e5ef7f9d.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Search "virtual machines" in Azure then select "+ Create" and "Azure virtual machine". You will then be prompted to sort the VM with the correct subscription and select the resource group you created in the step previously. For the image dropdown use "Windows 10 Pro, version 21H2" then name your virtual machine and select the region you would like your VM's IP location to reflect. Again, making sure it matches the resource group. 
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/232952064-f733035f-015c-4e5c-a8d5-a8ddd548bd9b.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create an username and password for the VM. In this example, I named my VM something easy to remember like "vm1" and created my admin password to be a password I use frequently that is at least 12 characters. Leave remaining settings at their default.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/232953745-f699f5ec-deab-4d6e-86ad-c7684769cbe2.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Check the box to confirm that you agree to use the licensing then select "Review + create".
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/232954288-2e3f006c-6006-42c3-85f6-f2febd4bcf91.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Review the current settings, the amount to be charged for running the VM, and wait for validation. Once you confirm that there are no errors then you can "create". Check your notifications in Azure to make sure that your VM finishes deploying before trying to access. Upon creation, a subnet mask will be created automatically. 
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/232955078-32f56e3e-59d1-42b0-b153-ec840ac56c01.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In your Windows Start menu, search for "remote desktop connection". Back in Azure, copy the public IP address of your newly created VM and paste into the Windows Remote Desktop connection then "Connect". 
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/232955573-b8cfcc94-81c2-4460-b3c4-803011eb5ed5.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You will then be prompted to enter the password but it may not be for the VM username that you created so you would want to login using "more choices" then "Use different account". Enter the VM username and password created earlier. You might be prompted to confirm the VM is a trusted connection, select "Yes". Your connection will then begin and behave as a separate computer with an operating system running Windows 10.
</p>
<br />

