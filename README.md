# Setting-Up-WordPress-on-EC2-with-RDS

## A complete step-by-step guide to setting up a WordPress on EC2 with RDS

### This project will demonstrate:

* Launch an an EC2 Instance and connect to the EC2 Instance via SSH

* Install an Apache Web Server

* Downloading WordPress and Files

* Set up AWS RDS

* Connect WordPress to RDS

  



#### Step-by-Step Instruction Guidance:

**LAUNCH AN EC2 INSTANCE AND CONNECT VIA SSH**

* Search and Select EC2 from AWS Searchabr
<p align="center">  
  <img src="resources/Select EC2 from AWS Searcbar.png" alt="Seklect EC2 from AWS Searchbar" width="900" />  
</p>  

* Select Instances from the left-hand navigation panel
<p align="center">  
  <img src="resources/Select Instance left handed navigation panel.png" alt="Select Instances" width="900" />  
</p>  

* Select from the top right the Launch instances button
<p align="center">  
  <img src="resources/Select Launch Instance from top right.png" alt="Select Launch Instancess" width="900" />  
</p>  

* Give a name to your EC2 Instance
<p align="center">  
  <img src="resources/Give your ec2 instance a name.png" alt="EC2 Instance Name" width="900" />  
</p>  

* Select a keypair
<p align="center">  
  <img src="resources/Select a keypair.png" alt="Select Keypair" width="900" />  
</p>  

* Select the Launch instance button 
<p align="center">  
  <img src="resources/Select end Launch instance button.png" alt="Select Launch Instance" width="900" />  
</p>  

* Select the EC2 Instance recently created
<p align="center">  
  <img src="resources/Serlect recently created Instance.png" alt="Select recently created Instance" width="900" />  
</p>  

* Select from the top right the Connect button
<p align="center">  
  <img src="resources/Select the Connect Button from top right.png" alt=" Select Connect Button" width="900" />  
</p>  

* Select the SSH client tab
<p align="center">  
  <img src="resources/Select the SSH client tab.png" alt="Select the SSH tab" width="900" />  
</p>  

* Open Command Prompt, navigate to the directory containing the key pair, and replace values as needed using the command below
<p align="center">  
  <img src="resources/SSH into command prompt command.png" alt="SSH into Command Prompt" width="900" />  
</p>  

  **INSTALL AN APACHE WEB SERVER**

  * Update the package list
 <p align="center">  
  <img src="resources/SSH into command prompt command.png" alt="Update the package list" width="900" />  
</p>  

  * Install the Apache web server
 <p align="center">  
  <img src="resources/command to install the Apache web server.png" alt="Install command Apasche Server" width="900" />  
</p>  

  * Start the Apache web server service
 <p align="center">  
  <img src="resources/command to start Apache service.png" alt="Start command Apache Server" width="900" />  
</p>  

  * Enable the Apache web server to start on boot
 <p align="center">  
  <img src="resources/enable apache service to start on boot.png" alt="Enablle Command start on boot Apache Server" width="900" />  
</p>  

  **DOWNLOADING WORDPRESS & FILES**

  * Navigate to the directory for the Apache Web Server
 <p align="center">  
  <img src="resources/Navigate to the Apache web server directory.png" alt="resources/Navigate to the Apache web server directory.png" width="900" />  
</p>  

  * Download the WordPress files
 <p align="center">  
  <img src="resources/Download Wordpress command.png" alt="Download Command Wordpress file" width="900" />  
</p>  

  * Extract the WordPress files
 <p align="center">  
  <img src="resources/Download Wordpress command.png" alt="Extract the Wordpress file" width="900" />  
</p>  

  * Navigate to the WordPress directory
 <p align="center">  
  <img src="resources/Navigate to Wordpress directory.png" alt="Navigate command Wordpress file" width="900" />  
</p>  

  * Rename the file by moving it
 <p align="center">  
  <img src="resources/rename the file by moving the file command.png" alt="Rename the file by moving it" width="900" />  
</p>  


  **SET UP AWS RDS**

* Search and Select Aurora and RDS from the AWS Searchbar
<p align="center">  
  <img src="resources/Aurarora and RDS AWS Searchbar.png" alt="Select Aurora and RDS AWS Searchbar" width="900" />  
</p>  

* Select the Easy Create option
<p align="center">  
  <img src="resources/Choose Easy Create option.png" alt="Select Easy Create" width="900" />  
</p>  

* Select MySQL option
<p align="center">  
  <img src="resources/MYSQL from options.png" alt="Select MYSQL" width="900" />  
</p>  

* Select Free Tier option
<p align="center">  
  <img src="resources/Choose free tier option.png" alt="Choose Free Tier" width="900" />  
</p>  

* Select database-test1
<p align="center">  
  <img src="resources/Select database-test1.png" alt="Select Database Test1" width="900" />  
</p>  

* Select a master-username
<p align="center">  
  <img src="resources/type username for database.png" alt="Select Master Username" width="900" />  
</p>  

* Select a master-password and then retype that master password underneath
<p align="center">  
  <img src="resources/Type a password underneath.png" alt="Select master-password" width="900" />  
</p>  

* Select the Create Database button
<p align="center">  
  <img src="resources/Create Database button at bottom.png" alt="Create Database button" width="900" />  
</p>  

**Connecting WordPress to RDS**

* Select the Endpoint from the newly created database
<p align="center">  
  <img src="resources/Select Endpoint details from completed setup database.png" alt="Select Endpoint " width="900" />  
</p>  

* Go back to the command prompt and type the following command
<p align="center">  
  <img src="resources/Go back to command prompt and type the following command.png" alt="Back in command-prompt" width="900" />  
</p>  

* Enter the following information where necessary, both when setting up the database and when copying the endpoint 
<p align="center">  
  <img src="resources/Type RDS setup info into appropiate places.png" alt="Enter RDS Setup Info" width="900" />  
</p>  


















##### Contribution Policy

This project is not accepting external contributions, including pull requests or feature requests.

It serves as a personal archive of my learning journey in applying foundational concepts in software development and version control. Active development is not ongoing, and external changes will not be integrated.

Thank you for your understanding.
