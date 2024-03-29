<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/d5216032-4621-413d-ad82-6af00f8c0a89"
"/>
</p>

<h1>Microsoft Azure: Creating a Virtual Machine</h1>
This is a walk-through on how to create a Virtual Machine with basic settings in Microsoft Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure 

<h2>Services Used</h2>

- Azure Virtual Machines

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Outlook email
- Azure subscription
- Internet service

<h2>Configuration Steps and Deployment</h2>
          
**1. On the Microsoft Azure Home page, under Azure Services, select 'Create a Resource'**

<p align="center">
<p>
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/c771f1f3-f21d-496a-9304-d1a734135410">
</p><p>


</p>
<br />

**2. On the next page, click on 'Create' under 'Virtual Machine'**

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/38833e0e-24d4-436a-a40c-57384811438a"
</p>


**3. You will fill out all the information required for basic setting (Project Details, Instance Details, Administrator account, and Inbound Port Rules)**

- Project Details: Select the subscription and resource group that you would like to use. If you want a new resource group to be created for your new VM, that will be done automatically (by default).

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/5bf0d65e-8431-4f2c-960b-778cddd80fd5">
</p>


- Instance Details: Select a name and a region for your VM; Select 'no infrastructure redundancy required' as a basic setting for your availability options; Select the base operating system/application also known as 'Image' (Windows or Ubuntu server, Windows 10 or 11, etc.)
; Lastly, select an appropriate VM size to support your workload (1, 2, 4 vcpus).

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/0ed884b7-42be-4d7b-ba28-649d632eaaed">
</p>

- Administrator Account: Create a username and password.

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/fa516dbd-0ab6-4cb5-8b05-968f2ad1d8f8">
</p>

- Inbound port rules: You may leave Inbound port rules configuration as the default selection, check the box to confirm Licensing, and click on 'Review + Create.'

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/9fe1792b-d44a-425c-af37-42cbaa8cc8cc"
</p>


**4. After the review process, you should see 'Validation Passed' at the top right corner of your screen. Once again, choose 'Create' (located at the bottom)**

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/bae90687-4f9a-4112-aadc-e0ecf2c65acd">
</p>

*If you don't see 'Validation Passed', you will need to go back and review what you did. You might have just missed checking a required box.* :relaxed:

**5. You will see every resource being created inside the VM while its deployment is in progress**

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/11baa8d8-7ca0-4488-b405-45ac831ae2f4">
</p>

**6. Once the VM deployment is complete, select 'Go to resource' to begin utilizing your newly created VM**
<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/501af060-276e-4b2c-9bb7-f809371be01e">
</p>

***References:***
- <a href="https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal">Quickstart: Create a Windows virtual machine in the Azure portal </a>
- <a href="https://www.canva.com/linkedin-banners/templates/">Create a LinkedIn Banner with Canva </a>





