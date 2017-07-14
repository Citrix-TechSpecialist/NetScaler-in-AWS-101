# Introduction to AWS and NetScaler
In this tutorial, we will explore the basics of AWS when provisioning:

1. Networking resources
2. Compute resources

As a pre-requisite for this tutorial, please sign up and create your own AWS Free Tier account from the [sign in page](https://console.aws.amazon.com/console/home)

Follow along via links to AWS tutorial content in the Table of Contents below. 

# Table of Contents

##Networking in AWS ([VPC](./VPC#VPC)) ##
1. [Overview](/VPC#VPC-Overview)
2. [Creating a VPC](/VPC#VPC-Wizard)
3. [Creating Three Subnets](./VPC#VPC-Subnets)
    * Management Subnet
    * Server Subnet
    * Client Subnet
4. [Creating Three Route Tables](./VPC#Route-Tables)
  * Configure the MGMT Subnet Default Route Table
  * Create and Configure the Server Subnet's Route Table
  * Create and Configure the Client Subnet's Route Table
5. [Summary](./VPC#VPC-Summary)

**Summary of [Network Topolgy after completion](VPC/images/Base-NTW-Topology.jpg)**

## Computing in AWS ([EC2](./EC2#EC2)) ##
1. [Overview](./EC2#EC2-Overview)
2. [Launch an Windows EC2 Instance (Client Network)](./EC2/Windows-EC2/README.md#EC2-Windows)
  * Overview EC2 Launch Wizard for Windows Server 2016 Instance
  * RDP into Windows EC2 Instance
  * Pull S3 Bucket files into the Windows Instance
  * Summary
3. [Launch a Linux EC2 Instance (Server Network)](./EC2/Ubuntu-EC2/README.md#Linux-EC2)
  * Overview EC2 Launch Wizard for Ubuntu Server Instance
  * SSH into Linux EC2 Instance, Update, and Install Pre-Reqs
  * Mount EFS volumes on the host
  * Host a WebApp on port 8080
  * Summary

**Summary of [Network Topology after completion](VPC/images/NS-NTW-Topology.png)**


  
  
