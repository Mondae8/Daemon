<h1>Hi, I'm Daemon! IT Cloud Specialist, Cloud Security Specialist, Cybersecurity Professional, Network Engineer and Project Manager

  
  
  
  
  <******Wireshark Ping Disney.com******>

  
  https://github.com/user-attachments/assets/daa21fe8-dd97-4150-8325-923b3559bb8d
# OS-Ticket-prereq3


<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Setup a Virtual Machine in Azure
- Install the OS Ticket requirements
- Install OS Ticket framework
- After Installation configuration of OS ticket


<h2>Installation Step 1 -Setup a Virtual Machine in Azure</h2>

 




To set up a Virtual Machine in Azure you will have to create a machine by pressing the create tab.
<p>
Now enter project details in resource group,Name it OS-Ticket.
  <p>
Next name the VM OSticket-vm.
    <p>
Select the image for Windows 10.
      <p>
Select a size of 2-vcpu or more
        <p>
Fill out user name and password.
          <p>
For Licensing please check the box.
            <p>
Please note the system pre fill most tabs and on this lab you will not have to change or adjust at this point.
              <p>
Now review and create Virtual Machine and notice it states Deployment in progress.
                <p>
If all Allocations are correct you will have succesfully created a Virtual Machine on your resource page with a valid IP addresse.
 <br />
<P>
 
</P>
  
<img src="https://i.imgur.com/fQ0LMOl.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/Nk76zt5.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/gtKVDtm.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/DiHCgLV.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/lIfT0RL.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/KES4AI6.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/mSZUu9b.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/0weHDLA.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/oxVaHJj.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/zNl5fus.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/d2bOUvT.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/Dz7njNQ.png" height="80%" width="80%" alt=" Steps"/> 
<img src="https://i.imgur.com/KIOXPBJ.png" height="80%" width="80%" alt=" Steps"/> 

  <br />
  <P><P>
   
  </P>
   
  </P>
  
<h2>Installation Step 2 -How to Install the OS Ticket requirements</h2>

<br />
<p>

 Open Remote Desk top and enter IP addresse from Virtual Machine and press enter.
 <p>
  Enter your credentials that you made prior and press enter.
  </p>
  You should be now logging in to the Virtual Machine on your Desktop.
  </p>
  <p>
  Once on the Virtual Machine Desktop open internet explorer and navigate to Google and download all requried files. 
  <p>
  </p>
  From this link [https://drive.usercontent.google.com/download?id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD&export=download&authuser=0]
  </p>
 
</p>

<img src="https://i.imgur.com/5QHNzKD.png" height="80%" width="80%" alt=" Steps"/>
<img src="https://i.imgur.com/PeMqNl3.png" height="80%" width="80%" alt=" Steps"/>
<img src="https://i.imgur.com/VHiOCR6.png" height="80%" width="80%" alt=" Steps"/>
<img src="https://i.imgur.com/q19BpWf.png" height="80%" width="80%" alt=" Steps"/>
<img src=https://i.imgur.com/oTfuD6T.png"" height="80%" width="80%" alt=" Steps"/>

</p>
<h2>Installation Step 2 -How to Install the OS Ticket requirements</h2>
<p/> 
Once files have been downloaded extract all and place on the desktop.
</p>
Select destination folder for desktop and press ok.
</p>
Now open control Panel and select Progams  and then Uninstall a program.
<p>
 
</p>
<p/>
On next window select Turn windows features on or off.
<p/>
  
<img src="https://i.imgur.com/gKTLTe1.png" height="80%" width="80%" alt=" Steps"/>
<img src="https://i.imgur.com/2t3Diqw.png" height="80%" width="80%" alt=" Steps"/>
<img src="https://i.imgur.com/P8gzBzq.png" height="80%" width="80%" alt=" Steps"/>
<img src=https://i.imgur.com/HsZThTq.png"" height="80%" width="80%" alt=" Steps"/>
<img src="https://i.imgur.com/kEgCfjH.png" height="80%" width="80%" alt=" Steps"/>
<img src="https://i.imgur.com/RkL3bde.png" height="80%" width="80%" alt=" Steps"/>

<p/>
</p>
<h2>Installation Step 2 -How to Install the OS Ticket requirements</h2>
<p/>


When the window pops open for Turn Windows features on or off.
<p>
 Expand Internet Information Services.
 <p>
 World Wide web Services.
  <p>
 Application Development Features.
<p>
 Then select CGI ,press ok and let system update.
</p>
 
 
 
</p>




<img src="https://i.imgur.com/DAsvV7c.png" height="80%" width="80%" alt=" Steps"/>
<img src="https://i.imgur.com/OrmkRF3.png" height="80%" width="80%" alt=" Steps"/>

<br/>












