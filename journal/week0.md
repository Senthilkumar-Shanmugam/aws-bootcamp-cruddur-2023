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
https://lucid.app/lucidchart/bcada147-71ca-49f4-b486-7cacb97cca57/edit?viewport_loc=15%2C-49%2C1357%2C596%2C0_0&invitationId=inv_55866404-1a11-483a-9714-4bb6f34cf4ca

![image](https://user-images.githubusercontent.com/5489060/219876016-cbf28ac6-4e62-4b82-9c83-295bca2e301b.png)


# Logical Design Diagram
I think authentication service dont need to communicate with backend. It could either use internal users or external auth providers. In this case i did not inlcude external auth provider, but i can change this diagram later to include that
![image](https://user-images.githubusercontent.com/5489060/219874145-4b875a42-fa43-49f5-8c72-6d67ec47fd3b.png)

https://lucid.app/lucidchart/aceb0af0-b5ff-4a10-a182-ff9c69ca8db0/edit?viewport_loc=-4%2C18%2C2040%2C896%2C0_0&invitationId=inv_1125757c-4fce-4aba-83e5-caa06969cd07

