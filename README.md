# Setting-Up-WordPress-on-EC2-with-RDS

## A complete step by step guide to setting up a Word Press on EC2 with RDS

### This project will demonstrate:

* Launch an an EC2 Instance and connect to the EC2 Instance via SSH

* Install an Apache Web Server

* Downloading Wordpress and Files

* Set up AWS RDS

* Connect WordPress to RDS

  



#### Step by Step Instruction Guidance:

**LAUNCH AN EC2 INSTANCE AND CONNECT VIA SSH**

* Search and Select EC2 from AWS Searchabr
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select Instances from the left hande d navigation panel
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select from the top right the Launch instances button
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Give a name to your EC2 Instance
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select a keypair
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select the Launch instance button
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select the EC2 Instance recently created
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select from the top right the Connect button
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select the SSH client tab
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Open Command Prompt, navigate to the directory containing the key pair, and replace values as needed using the command below
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  **INSTALL AN APACHE WEB SERVER**

  * Update the package list
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  * Install the Apache web server
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  * Start the Apache web server service
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  * Enable Apache web server to start on boot
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  **DOWNLOADING WORDPRESS & FILES**

  * Navigate to the directory for the Apache Web Server
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  * Download the WordPress files
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  * Extract the Wordpresss files
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  * Navigate to the Wordpress directory
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

  * Rename the file by moving the file
 <p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  


  **SET UP AWS RDS**

* Search and Select Aurora and RDS from the AWS Searchbar
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select the Easy Create option
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select MySQL option
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select Free Tier option
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select database-test1
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select a master-username
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select a master-password and then retype that master-password underneath
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Select the Create Database button
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

**Connecting WordPress to RDS**

* Select the Endpoint from the newly created database
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Go back to the command prompt and type the following command
<p align="center">  
  <img src="resources/select s3 from aws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  

* Enter the following information where neccasasry from when both setting up the database and when copying the endpoint 
<p align="center">  
  <img src="resources/select s3 from  ws searchbox.png" alt="Type S3 from AWS Searchbar" width="900" />  
</p>  


















##### Contribution Policy

This project is not accepting external contributions, including pull requests or feature requests.

It serves as a personal archive of my learning journey in applying foundational concepts in software development and version control. Active development is not ongoing, and external changes will not be integrated.

Thank you for your understanding.
