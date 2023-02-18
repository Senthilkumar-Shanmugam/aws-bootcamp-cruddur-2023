# Week 0 — Billing and Architecture

# Homework Challange
1.Destroy your root account credentials, Set MFA, IAM role.. Already I have an Oganization set up with SSO with 3 member accounts. Root user is setup with MFA and created an admin user for all activties
2. Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a service health issue.
3. Review all the questions of each pillars in the Well Architected Tool (No specialized lens)
4. Create an architectural diagram (to the best of your ability) the CI/CD logical pipeline in Lucid Charts
5. Research the technical and service limits of specific services and how they could impact the technical path for technical flexibility. 

# Conceptual Design 

# Logical Design Diagram
I think authentication service dont need to communicate with backend. It could either use internal users or external auth providers. In this case i did not inlcude external auth provider, but i can change this diagram later to include that
![This is an image](Crudder_Logical_Diagram.jpeg)
