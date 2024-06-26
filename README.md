# configure-VM
![image](https://github.com/tahinajamison/configure-VM/assets/171196211/60814666-7ca0-4683-8825-fb3e6877fc53)
                                                          
<h1>Creating a Virtual Machine</h1>
This tutorial outlines the implementation of Virtual Machines within Azure.<br />


<h2>Video Demonstration</h2>

- ### [YouTube:

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/tahinajamison/configure-VM/assets/171196211/4caa6c1f-2dc0-40c1-8909-8a061c733cfd)

- For this lab we will need to open the web browser and type in portal.azure.com
- You would need to create a subscription and that'll give $200 worth of Azure credits in which you'll have 30 days to use 
- In order to create a virtual machine, you would first need to create a resource group
- You have the choice of selecting the resource group icon or typing it in the search bar
  
  ![image](https://github.com/tahinajamison/configure-VM/assets/171196211/9c3344c1-31d8-4eca-9ef9-a757210afb18)

- Next you will fill out the information below, create a name for the resource group, then select the region you're in.
- Once information is filled out, Select "Review + Create"
- After it'll state validation has passed in green, and now you can click "Create" at the bottom, and now you have a resource group.
  
  ![image](https://github.com/tahinajamison/configure-VM/assets/171196211/e76639f6-b340-4419-8a36-8055a24b9158)
- Next you will select Microsoft Azure located at top left hand corner to bring you back to the home screen
- Now we can begin to create our virtual machine
- You have the option to either select the VM icon or type in the search bar
- Once selected, click on the plus sign next to "Create" then select the first option, "Azure Virtual Machine"
- We will fill out the information like we did for the resource group
- You will also select the resource group that already exists and that is where the virtual machine will be stored
- Create a name for the VM, select the region, then for image select your operating system, under size select the virtual cpu you'd like to use
- Next create a username and password and check the box to confirm licensing
- Lastly you'd select "Review + Create".
- Once completed it'll say validation passed in the green at the top of the screen. Bear in mind, this may take a few minutes to complete.

-   CONGRATULATIONS ON CREATING A VIRTUAL MACHINE!      
</p>
<br />


![image](https://github.com/tahinajamison/configure-VM/assets/171196211/dcadfcfe-7399-4370-a212-0148f5661d33)

<h2>REMOTE DESKTOP WITH MacOS</h2>

- Now that you have created your virtual machine, if you want to go back and review, you can click on Microsoft Azure to return to the home page and either select the icon or type in the search bar

- Once you've clicked on the VM you created, it'll display all the information and resources in regards to the VM

-Window users also have access to remote desktop, an image is displayed below for reference

![image](https://github.com/tahinajamison/configure-VM/assets/171196211/95fae60f-cf86-4695-b478-7c2fbcd0ea07)

- To utilize the remote desktop, you will need the public ip address which can be found once you open your VM

- Once you have the ip address, you can now enter in the username and password you created initially for your VM

- A warning message may appear, but you can disregard and proceed forward and click yes. Now you can paste the ip address when prompted, and now you have access to your Virtual Machine.

- Okay, for Mac users, you can download "RD Client" from the Apple Store and its free, its the orange icon

- The steps are the same, you select "Add PC", enter the public ip address, then enter in the username and password for the VM and click save.

- Now you have created your virtual pc within the app

- Click on the PC and your virtual machine should load onto the Mac.

- Its important to delete virtual machine, when done,  to avoid using all your credits.

- Return to azure portal and select the resource group then select delete. Since VM is within resource group it will delete as well. But double check to make sure everything is deleted, including additional VM that could have been created such as "Networkwatchers"
  
