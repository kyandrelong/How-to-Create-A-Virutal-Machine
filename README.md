<h1>How to set up a Virtual Machine</h1>
<img src="https://i.imgur.com/h6vJS9e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Step by step tutorial on how to set up Virtual Machine inside Azure.
<h1>Virtual Machine - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of VM.<br />




<h2>Environments and Technologies Used</h2>

- Remote Desktop
- Microsoft Azure (Virtual Machines/Compute)
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Sign up With Azure/ Create a Subscritption
- Make a resource group
- Set up VM and back test it


<h2>Virtual Machine Set Up</h2>

<p>
<img src="https://i.imgur.com/1IAHQ71.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1st Sign up with Azure using your email. Then you'll need to create a subscription to seperate cost. Dont worry its completely free. Nothing will be charged to your card. 
</p>
<br />

<p>
<img src="https://i.imgur.com/QvAISx3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Create a resource group. Simply go at the top of the search bar in azure and type in "Resource group". Select and it should take you to another screen as seen on the picture. Start by creating your resource group name. Creative but easy to remember. Make sure to select region closest to you. After you'll select review and create. Wait until its completed and you should shortly see the progress complete message. 
</p>
<br />

<p>
<img src="https://i.imgur.com/apJQ5N9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Final and the longest step. Go back into the azure search bar and type in "Virtual Machine". After selecting it should take you the screen above and select create, azure virtaul machine. From there you want to select the resource group you created in step 2. Choose a unique virtual machine name, then scroll down and select region closest to you. After scroll down some more till you see "image" and select windowns 10. Once you clicked windows 10 scroll down some more and look for size. Choose an option that has two vcpu's. From there go down the page until you find username and password. As stated earlier choose something creative and rememeber to save it somehwere so you don't forget cause we will need it to login later. Click I confirm box at the bottom and hit create twice. Once VM (virtual machine) is created click on the name of your VM to view and copy the public IP address. Now to back test simply go to your windows app search bar and type in "remote desktop connection". For MacOS users use the app you downloaded in the previous step. Once remote desktop app pops up paste the IP address from your VM. From there type in username and password that you used to create your VM to login to the next screen. Once you succesfully login you'll have full access to your VM. 
</p>
<br />
