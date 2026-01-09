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

* Select Instances from the left hande d navigation panel

* Select from the top right the Launch instances button

* Give a name to your EC2 Instance

* Select a keypair

* Select the Launch instance button

* Select the EC2 Instance recently created

* Select from the top right the Connect button

* Select the SSH client tab

* Open Command Prompt, navigate to the directory containing the key pair, and replace values as needed using the command below

  **INSTALL AN APACHE WEB SERVER**

  * Update the package list
 
  * Install the Apache web server
 
  * Start the Apache web server service
 
  * Enable Apache web server to start on boot
 
  **DOWNLOADING WORDPRESS & FILES**

  * Navigate to the directory for the Apache Web Server
 
  * Download the WordPress files
 
  * Extract the Wordpresss files
 
  * Navigate to the Wordpress directory
 
  * Rename the file by moving the file
 

  **SET UP AWS RDS**

* Search and Select Aurora and RDS from the AWS Searchbar

* Select Easy Create option

* Select MySQL option

* Selct Free Tier option

* Select database-test1

* Select a master-username

* Select a master-password and then retype that master-password underneath

* Select the Create Database button

**Connecting Wordpress to RDS**

* Select the Endpoint from newly created database

* Go back to command prompt and type the following command

* Enter the following information where neccasasryfrom when both setting up the database and when copying the endpoint 


















##### Contribution Policy

This project is not accepting external contributions, including pull requests or feature requests.

It serves as a personal archive of my learning journey in applying foundational concepts in software development and version control. Active development is not ongoing, and external changes will not be integrated.

Thank you for your understanding.
