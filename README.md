<h1>Installing Active Directory</h1>


<h2>Description</h2>
<p>In this section, I will install Active Directory on the Server device. This will also allow me to create a new domain and manage users and services.</p>


<br />

<h2>Step-by-Step Walk-Through:</h2>


<p align="center"> 
STEP 1: <br/>
<img src="https://i.imgur.com/f1giJLB.png" height="70%" width="70%"/> </p>


<p align="center">This is a critical step, and I'll be creating a "Domain" and adding "Active Directory". As you can see, I'm in the "Server Manager" section, from where I can carry out those actions.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 2: <br/>
<img src="https://i.imgur.com/I9M3LoZ.png" height="70%" width="70%"/> </p>


<p align="center">To install Active Directory and create a domain, I first click the "Manage" button, then "ADD ROLES AND FEATURES".</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 3: <br/>
<img src="https://i.imgur.com/hlZ8IBh.png" height="70%" width="70%"/> </p>


<p align="center">This is the page that appears when you click on "Add roles and features". As you can see, this is the installation wizard for installing "Active Directory" and creating a new "Domain." I then select "NEXT" to move on to the next step of the installation.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/XoHjEC3.png" height="70%" width="70%"/> </p>


<p align="center">In this part, I select the first option: role or feature-based installation. Selecting this option will allow me to create a domain controller thereby creating an actual domain.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/yhOFMqR.png" height="70%" width="70%"/> </p>


<p align="center">Now it's asking me to choose a server to install "Roles and Features". In this situation, I chose the single choice available: "Server 2016" with a pre-assigned IP address of 10.0.2.15. I then move on to the next phase.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/6fCFnu6.png" height="70%" width="70%"/> </p>


<p align="center">I've been shown a list of features that I can add to the virtual machine's "Server Manager". In this example, I have chosen "Active Directory Domain Service".</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/01GhNcd.png" height="70%" width="70%"/> </p>


<p align="center">Here's a confirmation of the installation settings that I've selected. In this case, it includes everything I need for the time being, so I move on to the following step to complete the installation.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/hznXXHe.png" height="70%" width="70%"/> </p>


<p align="center">As indicated by the progress indicator above, the installation has now completed successfully. However, more configuration is required to make the device a "domain controller". The picture above shows that it is requesting me to "Promote" the server to a domain controller. In this scenario, I click it to proceed to the next step.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 4: <br/>
<img src="https://i.imgur.com/Dli1UE1.png" height="70%" width="70%"/> </p>


<p align="center">This stage requires me to create a new domain name for this lab-based project. In my instance, I actually need a new domain because there is no previous domain, therefore I click "Add a new forest". I then choose a name for the domain that I want to create, I've named it as "office123.com". I then click "Next" to move on to the next phase.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/RgQvddc.png" height="70%" width="70%"/> </p>


<p align="center">In this phase, I've set a password for the "DSRM". The password I've set is "DomainController123". The "DSRM" enables administrators to perform crucial maintenance and recovery operations when the Active Directory database is faulty, inaccessible, or experiencing problems.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/J0lM2v1.png" height="70%" width="70%"/> </p>


<p align="center">Here, it asks me to have a review of all the options that I've chosen and configured. In this scenario, everything appears good, so I decide to move on to the next stage.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/5hgJp5L.png" height="70%" width="70%"/> </p>


<p align="center">As you can see, it is installing, and once finished, it will promote this device to a "Domain Controller". After the installation is complete, the device will reboot.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/Ubnzi5n.png" height="70%" width="70%"/> </p>


<p align="center">The device is rebooting, which will successfully setup all of the adjustments I made in the installation phase.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 5: <br/>
<img src="https://i.imgur.com/NpDiTZK.png" height="70%" width="70%"/> </p>


<p align="center">The device has rebooted, and I am back in the "Server Manager". I go to the "TOOLS" section and notice that "Active Directory Users and Computers" has been installed. As you can see, it was successfully added, and I can now manage the domain, as well as its users and computers. Now, I click on "Active Directory Users and Computers".</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/c3uEnvp.png" height="70%" width="70%"/> </p>


<p align="center">This is "Active Directory Users and Computers", and from here I can access the domain controller. You can see that the domain name I generated is there, as are all of the folders (Organisational Units). From here, I can control the domain, as well as the users and computers within it.</p>



<a href="https://www.example.com">
  <button>NEXT</button>
</a>

