# AWS-Learning
30 days course for AWS
https://youtu.be/sFXU9n9-6iI?si=wre_4FEh11zzMD8Q 
ROADMAP FOR CLOUD ENGINEER

Steps:

Get the fundamentals
Why cloud exists
Business Benefits

Networking
Operating System
Virtualisation(heart of cloud computing)
Databases

Learn to Code

Learn Terraform
Learn Python programming language / learn Python Fundamentals

Diving into cloud

Amount of services you have to learn

To know AWS - most hybrid cloud
   ,Azure/GCP

Free 12 Week Bootcamp

Get Certified

Obtain foundation level certification

Projects

First project → Setup a virtual machine
Second project → Cloud Storage Solution
Third → Deploy a webapp – use HTML or React or using Cloud services

You need to firstly build it using the console and then rebuild infrastructures code such as Terraform - widely  using in the cloud industry, 

Make a resume using cloud - using number of different services along with cicd and cloud

Networking   
On Twitter
X x     — use the #100daysofcloud 
Apply Jobs
Post weekly blogs on linkedin on freelance gigs — do it every single week
Get Specialization

Cloud Security Devops  /
Machine Learning in the Cloud
→ Pick one route ,stick on one

Never stop learning
New tools / services are coming out


Free 12-week boot camp
AWS provide a program course →AWS re/Start   – Free 12-week Training program – AWS fundamentals

yyyyy

Amazon Web Services - AWS Zero to Hero Series

16/06/2025 

Day-0

Difference between Private & Public Clouds


Identity & Access Management
 
Which is basically used for accesses and 

Day - 1
Introduction to AWS
What is Cloud?
Public Vs Private Cloud
Why is public cloud so popular?
Why AWS?
Trends of people moving back to Private cloud?
Create an AWS account and get started


What is Cloud?
 What is the cloud?
The cloud means storing and accessing data, apps, and services over the internet instead of your own computer.

🔹 Example:
When you save a photo in Google Drive – it’s saved in the cloud.
When you watch a movie on Netflix – it’s streamed from the cloud.
🔹 Real meaning:
The cloud is just powerful computers (called servers) in big data centers around the world.
You connect to them using the internet.
🔹 What can the cloud do?
Store files
Run apps (like Gmail, Zoom)
Host websites
Backup data
Analyze big data
Provide virtual machines (servers)
🔹 Simple comparison:
Your Computer
The Cloud
Limited space & power
Large, powerful remote servers
You manage everything
Cloud company manages for you
Data stored locally
Data stored on internet servers


Before the past 20 years, there were no cloud platforms, so whenever we needed to deploy the application, we had to buy the servers physically from different regions of the world and had to configure their network and deploy the application into those servers. After deploying, suppose we require only 1 GB of RAM for maintaining, we don't have an option to buy only 1 GB RAM servers. We have to buy 100 GB of RAM for the servers. From this the major drawback is that there is a lot of waste of RAM usage, and more cost to maintain servers physically, and it is difficult overall to maintain physical servers. So, to encounter this problem, AWS came forward and introduced its cloud services by giving only the required number of servers to the users and paying only for what they have used.

Old-time companies buy servers and deploy applications
Data center → a place where all the servers are stored and all the configurations are done for the servers
  
Most companies buy servers from organisations like IBM, or they create them.

 For buying a server has 100 GB RAM,100 CPU, if you run one application using 1GB RAM and CPU that the remaining 99 GB RAM & CPU will be wasted for solving which introduces virtualisation. 


What is virtualization?
Virtualization means dividing one real server into many virtual servers.
It’s like:
You have one big house (real server),
And you split it into many small flats (virtual servers),
Each flat works independently, like a mini-house with its own people (apps, OS).
🔹 In cloud computing:
Cloud providers use virtualization to make many virtual servers on fewer physical machines.
Each user gets their own virtual machine (VM), but in reality, it runs on shared physical hardware.
🔹 Benefits:
Use resources better
Run multiple VMs on one machine
Save cost
Easy to move, copy, or scale
Example:
You want a server for your website. Instead of buying a full machine, cloud providers give you a virtual server using virtualization. It works just like a real one!

Public Vs Private Cloud

Private cloud is simply buying servers physically and deploying our applications without the help of any cloud providers. 
On the other hand Public cloud is the cloud where we can buy servers from the cloud providers.
 
Private Cloud (Your organization manages)
The cloud environment is used only by your company.


You or your IT team handles:


Setup
Security
Maintenance
Monitoring
Can be:
On your servers (on-premises)
Or hosted on a service like AWS, but still isolated (using VPC, etc.)


More control, more security, but higher cost and responsibility.
Example: A bank builds its private cloud for internal apps.
🔹 Public Cloud (You use, provider manages)
Services are provided by companies like AWS, Microsoft Azure, or Google Cloud.
You use the resources (like virtual servers, storage, and databases).
The cloud provider manages everything behind the scenes.


Physical servers
Network
Power and cooling
Hardware upgrades


You only manage your applications and settings.
Example: You create an EC2 instance in AWS and deploy your website.
🔹 Simple Comparison:
Feature
Private Cloud
Public Cloud
Ownership
Your company
AWS / Google / Microsoft own it
Management
You manage everything
The provider manages hardware, etc.
Users
Only your organization
Many customers (securely separated)
Cost
High (hardware, staff)
Pay for what you use
Example
The company’s internal cloud with VMs
EC2 in AWS, Google Cloud, Azure



Why Public cloud better than private?

1. Lower cost compared to private cloud.
2. Public cloud cuts down the major headaches for its users, such as maintaining servers and checking connections, and giving network configurations, as everything will be taken by cloud providers only. 
No Infrastructure Headache (Most important reason)
You don’t need to buy, build, or manage physical servers, networks, or data centers.
The cloud provider (like AWS, Google, or Microsoft) does all that for you.
No worries about:
Hardware failure
Power backup
Cooling
Server upgrades
Network setup
🔸 This saves time, effort, and skilled manpower.
2. Cost-Effective (Money)
You pay only for what you use (like rent).
No big upfront investment in hardware.
Easily scale up or down as your needs change.
Perfect for startups, small businesses, or fast-growing companies.
How is AWS better than others?
First comer in the market
AWS, Azure, GCP —the 3 main cloud platforms, but apart from that, Oracle Cloud, Digital Ocean, which are cloud providers
Why AWS is popular —> first popular mover advantage 
First comer in the market
Pioneers of cloud
They have started the entire cloud concept
Many companies started cloud, but started with AWS
Less maintenance 
Why is AWS better than others?
1. Learn Cloud Repartiation




AWS is the first cloud provider in the industry, holding a first-mover advantage.
2. AWS has the majority of the market share and offers a broader range of services. So, many companies are preferring AWS over other cloud providers. 

AWS Sign In
Yes I Done

Day 2 -17/06/2025
AWS IAM
What, Why
Users
Groups
Policies
Roles
IAM is an AWS service is solves the problem of authentication and authorisation
If there is an AWS account —AWS admin or a user creates an account in AWS, the user has root access to that account. 
18/06/2025
To the AWS the user has different access, but one thing delete from the AWS knowingly/unknowingly to the user — it is a primary false alarm —its permanently deleted from the AWS to solve this introduced—--IAM
IAM → Is an AWS service doing authorisation and authentication
IAM solving the problem of authorisation and a
E.g.: an employee 501 goes to AWS, then AWS gives him a user ID and password,, ie policies 
You need to enter a user into AWS, you need to attach some policies → which means some authentication.
Whenever you create a user you attach some policies to that user.
When you are not attaching any policies to that user the user just enters the AWS, user cant do nothing.
