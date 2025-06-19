IAM
 --- is solving the problem of authentication and authorisation in AWS using IAM

 - Rules
 - Policies
 - Groups
 - Roles
to add a new user into AWS that means creating an **Authentication**  --- you adding a new user you also auto attaching some **policies** to that user.
- Groups--every time new user joinn to aws and leaving ,every time join a new user ,attach some policies to it, its make manual efficiency so that,
      - You will automate these things, when a user create the policy also attached
      - that means **IAM **, it is the service
* Roles
  - is related to user
  - creating a DB services in AWS , developer has a private cloudd in aws,, a customer try to access the private cloud
      application is not a role , application accesing something from the AWS
   to create arole when you access the AWS application , just use the role 
