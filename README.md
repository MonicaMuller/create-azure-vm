<p align="center">
<img src="https://i.imgur.com/Bp7tRX1.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>
<h1>Creating a Virtual Machine (VM) in Microsoft Azure</h1>
In this project, I created a virtual machine in Azure and viewed the created topology using Network Watcher.<br />


<h2>Requirements</h2>

- Computer with internet connection
- Microsoft Azure account
  - Credit card (required for free Azure credits)

<h2>High-Level Steps</h2>

- Select “Virtual machines” and select to Create an “Azure virtual machine”
- Fill in the required fields on the “Basics” page
- Click “Review + create”
- Click “Create” if the VM has passed validation
- View newly created VM in Network Watcher
- Delete Resource Groups to minimize charges to free Azure credits

<h2>Synopsis</h2>

<p>
<img src="https://i.imgur.com/zkr3A9P.png" height="70%" width="70%"/>
</p>
<p>
To get started on creating the virtual machine, I searched for “virtual machine” in the search bar at the top of the Azure homepage and selected “Virtual machines.” I clicked “Create” in the top left corner (the blue “Create” button in the middle of the screen also works) and then selected “Azure virtual machine.”
</p>
<br />

<p>
<img src="https://i.imgur.com/bwTogp0.png" height="50%" width="50%"/>
</p>
<p>
<img src="https://i.imgur.com/3h91vqh.png" height="50%" width="50%"/>
</p>
<p>
The first page is the “Basics” page, where I filled in the required fields. For the Resource group, I made a new one by selecting “Create new” and also selected an appropriate region based on my location. The location you select can affect your options for the “Size” field, so this may need to be tinkered with a little. Don’t forget to check the box under Licensing! Once I was done filling this page out, I clicked “Review + create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/ksIytig.png" height="50%" width="50%"/>
</p>
<p>
Before the VM could be created, I had to make sure it passed validation. Once the message at the top confirmed that everything was set up properly, I clicked “Create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/3iB9u1P.png" height="70%" width="70%"/>
</p>
<p>
It took a bit of time for the VM to be set up by Azure, but once it was done, I was able to look at the configuration of my VM. I made a mental note of the location of the public and private IP addresses on this page, since finding this information would be important for future labs.
</p>
<br />

<p>
<img src="https://i.imgur.com/J9BB8fA.png" height="70%" width="70%"/>
</p>
<p>
Out of curiosity, I viewed the various components of my new VM using Network Watcher in Azure. As you can see, when you create a VM, it’s not just the virtual machine itself that is created. Along with the VM (VM-1), Azure also created a virtual network (VM-Lab-vnet), a subnet (default), a virtual NIC (vm-1960), a Network Security Group a.k.a. firewall (VM-1-nsg), and a public IP address (VM-1-ip).
</p>
<br />

<p>
✨ And that’s how I created a virtual machine in Azure! If you do the same, don’t forget to delete any Resource groups that were created if you want to minimize the charges to your free Azure credits.
</p>
<br />
