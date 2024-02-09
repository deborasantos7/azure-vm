<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/e8c04827-d38a-469d-a627-0ea2fa739730"
"
"/>
</p>

<h1>Microsoft Azure: Creating a Virtual Machine</h1>
This is a walk-through on how to create a VM with basic settings in Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Outlook email
- Azure subscription
- Internet Service

<h2>Creating a New VM Steps</h2>
          
**1. On the Microsoft Azure Home page, under Azure Services, click on “Create a Resource”**

<p align="center">
<p>
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/2bc84550-df99-462b-8008-3beab6d99292"
"/>
</p><p>


</p>
<br />

**2. On the following page, click on "Create" under "Virtual Machine"**

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/170a6f81-ddf1-4427-8d36-6aa3e69a1e3e"
</p>


**3. You will fill out all the information required for basic setting (Project Details, Instance Details, Administrator account, and Inbound Port Rules)**

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/2be95815-086b-4268-ae94-724fa2cb9bba">
</p>

*3.1- Project Details - Select the subscription and resource group that you would like to use. If you want a new resource group to be created for your new VM, that will be done automatically (by default).*

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/3fdeaab6-24b7-4a28-b4b5-c215d082e31e">
</p>

*3.2- Instance Details - Select a name and a region for your VM; Select "no infrastructure redundancy required" as a basic setting for your availability options; Select the base operating system/application aka "Image" (Windows or Ubuntu server, Windows 10 or 11, etc.)
; Lastly, select an appropriate VM size to support your workload (1, 2, 4 vcpus).*


<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/f0d573f5-64d8-4529-8ac2-86e9cf0dd147">
</p>
          
*3.3- Administrator Account - Create a username and password.*

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/d4332f9a-3aa4-4a07-8d07-81726bcaeedf"
</p>

*3.4- Inbound port rules - You may leave Inbound port rules configuration as the default selection, check the box to confirm Licensing, and click on "Review + Create"*

**4. After the review process, you should see "Validation Passed" at the top right corner of your screen. Once again, hit "Create" (located at the bottom)**

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/116d9961-4953-4340-9528-d881d3eba2a6">
</p>

**5. You will see every resource being created inside the VM while its deployment is in progress**

<p align="center">
<img src="https://github.com/deborasantos7/azure-vm/assets/158119574/95451aa0-410a-44e8-ab0b-6bb20b1173c0">
</p>



Deployment complete ![image](https://github.com/deborasantos7/azure-vm/assets/158119574/5fc3d730-d6b7-4754-bedd-44689d50c795)
VM not ready ![image](https://github.com/deborasantos7/azure-vm/assets/158119574/3759338e-3d0d-4b92-8809-09e2131daedd)
Redeploy/reapply 1 ![image](https://github.com/deborasantos7/azure-vm/assets/158119574/7b625f18-5020-4ae2-8b37-4c53650e3328)

Redeploy/reapply 2 ![image](https://github.com/deborasantos7/azure-vm/assets/158119574/8a27f1aa-8c78-467a-9601-d687bb3ed2c4)




