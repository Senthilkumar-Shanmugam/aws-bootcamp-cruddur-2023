# Week 0 — Billing and Architecture

# Homework Challange
1.Destroy your root account credentials, Set MFA, IAM role..  I Already have an Oganization set up with SSO with 3 member accounts. Root user is setup with MFA and created an admin user for all activties

# Setting up AWS CLI in gitpod workspace and setting Budget and Alarms using CLI

## Budget setup using console UI

![image](https://user-images.githubusercontent.com/5489060/219870559-c943eef3-0415-4ee5-8019-f55084fddac5.png)

## setup second budget using AWS CLI in gitpod terminal
![image](https://user-images.githubusercontent.com/5489060/219872038-7a50f2df-4ff0-4e28-8c10-4b47c64379f0.png)

## create Billing alarm using CLI
![image](https://user-images.githubusercontent.com/5489060/219872526-35940e1e-d919-4f02-9ddd-5eed259acb01.png)


# Conceptual Design 

# Logical Design Diagram
I think authentication service dont need to communicate with backend. It could either use internal users or external auth providers. In this case i did not inlcude external auth provider, but i can change this diagram later to include that
![This is an image](Crudder_Logical_Diagram.jpeg)
