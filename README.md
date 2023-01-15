<p align="center">
<img src="https://i.imgur.com/MMeeQdU.png" height="40%" width="40% alt="osTicket logo"/>
</p>

<h1>Step by Step How to make Virtual Machines (VM) with Microsoft Azure</h1>

<p align="left">

<h2>Environments and Technologies Used</h2>
 
- Microsoft Azure [(Link here!)](https://azure.microsoft.com/en-us/free/search/?&ef_id=Cj0KCQiA_P6dBhD1ARIsAAGI7HB9MnWM-wkQ-x0TEKP1HAlYk6pLXTlzUqVNw3nCU_BGULPeqXXjQKQaAlAZEALw_wcB:G:s&OCID=AIDcmm5edswduu_SEM_Cj0KCQiA_P6dBhD1ARIsAAGI7HB9MnWM-wkQ-x0TEKP1HAlYk6pLXTlzUqVNw3nCU_BGULPeqXXjQKQaAlAZEALw_wcB:G:s&gclid=Cj0KCQiA_P6dBhD1ARIsAAGI7HB9MnWM-wkQ-x0TEKP1HAlYk6pLXTlzUqVNw3nCU_BGULPeqXXjQKQaAlAZEALw_wcB)
- Computer (I am using Windows 10) with internet connection

<h2>Operating Systems Used </h2>

- Windows 10

<h2>List of Prerequisites</h2>

- Microsoft Azure account (When you start free trial, $200 is given to your account for first 30 days)

<h2>Creating the Virtual Machine</h2>

<p>
<img src="https://i.imgur.com/TvlmMme.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, log into your Microsoft Azure account, you'll need to make one if you don't already have one. You can start with a free trial and Azure will give you $200 for your first 30 days for starting your account!
</p>
<br />

<p>
<img src="https://i.imgur.com/hO1gFK6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you log into your Azure account, your portal should look like this, the search bar at the top will be your best friend when looking for specific services. In our case, we will be typing virtual machines in the search bar on the top (or click the little virtual machine logo under the search bar).
</p>
<br />
</p>
<br />
                                                                                                 <p>
<img src="https://i.imgur.com/VvgIIFy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you click on Virtual Machines, you have the option to create one. Click the blue "Create" in the middle and click the first drop down option that says "Create a virtual machine hosted by Azure".
</p>
<br />
</p>
<br />
                                                                                                 <p>
<img src="https://i.imgur.com/u0C6RaY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Here you are creating the details of your Virtual machine. It will start by asking you the basics of what subscription and "Resource Group" that you want to use. You can just make a resource group right now by clicking the blue "Create new" under resource group; I am naming mine "ExampleResource" (you can name it anything you want).
</p>
<br />
</p>
<br />
                                                                                                 <p>
<img src="https://i.imgur.com/Kv0xwPb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As you scroll down, you will name your Azure Virtual Machine (I am naming mine ExampleVM). You can choose your region, and operating system (for this example, I chose Windows 10 Pro, version 21H2 - x64 Gen2). After you choose your operating system, you can select the specs based off of your needs, the stronger your system, the more Azure will charge you. After that, you will be making your log in information into the Virtual Machine (My username for this example is ExampleVM1). Be sure to remember this username and password!
</p>
<br />
</p>
<br />
                                                                                                 <p>
<img src="https://i.imgur.com/1kKpkZF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Scroll down all the way to the bottom and there will be a Licensing check mark confirming about hosting rights; go ahead and click and check mark that (otherwise it will not let you create the VM). Go ahead and click the blue "Review + create" box on the bottom left. Azure will then validate everything and it may take a few seconds to do so.
</p>
<br />
</p>
<br />
                                                                                                 <p>
<img src="https://i.imgur.com/MBX7FUS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If everything goes well, you should have a green check mark that also says "Validation passed" at the top. Now click the blue "Create" box at the bottom left of the screen. It will also take a few seconds for Azure to create your virtual machine.
</p>
<br />
</p>
<br />
                                                                                                 
<img src="https://i.imgur.com/WtTEgKI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4.5
</p>
<br />
</p>
<br />
                                                                                                 
<h2>The Fun Part: Accessing Your Newly Created VM!</h2>                                                                                                 

<img src="https://i.imgur.com/3U3RNqs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5
</p>
<br />
</p>
<br />
                                                                                                 
 <img src="https://i.imgur.com/hhZbAY6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6
</p>
<br />
</p>
<br /> 
                                                                                                  
<img src="https://i.imgur.com/Z4cG6aT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7
</p>
<br />
</p>
<br />
                                                                                                 
<img src="https://i.imgur.com/Jkzk3BW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8
</p>
<br />
</p>
<br />
                                                                                                 
<img src="https://i.imgur.com/Bq1iEwl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9
</p>
<br />
</p>
<br />
                                                                                                 
<img src="https://i.imgur.com/RrDkc2J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
10
</p>
<br />
</p>
<br />
                                                                                                 
<img src="https://i.imgur.com/vsgEYWE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
11
</p>
<br />
</p>
<br />                                                                                                 
