# Week 0 — Billing and Architecture
ARCHITECTURE DIAGRAM
https://lucid.app/lucidchart/a03100ec-f8e9-4cb0-8c28-7f0dddb33f71/edit?viewport_loc=-507%2C-253%2C1480%2C673%2C0_0&invitationId=inv_e6a8b67a-2cb8-420d-acdb-f43c9ed5ec50
![Lucid Architecture Diagram](https://user-images.githubusercontent.com/75304701/219485598-261c5f9e-411f-40ca-a830-fea79277022e.png)
Above is the link to my Lucid Architecture chart which i created for the Crudder app.![Lucid Architecture Diagram](https://user-images.githubusercontent.com/75304701/219486026-19aa4196-34da-420b-ba7d-2bfd0e2147e9.png)
My user Mr Big Fish logs into the application using amazon Cognito which gies through AWS WAF for security reasons before getting into my VPC. 
Once inside the VPC, it reaches the Application Load balancer which regulates the traffic flow.
I decided to use two seperate containers, one for the frontend and the other for the backend.
I used two databases, RDS and DynamoDb which are stored in a private subnet.
Cloudfront is used for distributing content alongside Route 53 which send the requeted content to the user.


AWS IAM
![AWS IAM](https://user-images.githubusercontent.com/75304701/219489592-e596eaaf-fc39-4b21-97ac-ca363e098a7d.png)

AWS BUDGET AND BILLING
![AWS Budeget](https://user-images.githubusercontent.com/75304701/219489685-0fcf6669-4e19-455b-bf65-864427ccfb12.png)

AWS CLOUDWATCH
![Cloudwatch Alarm](https://user-images.githubusercontent.com/75304701/219489780-776a97f0-eceb-490a-afcd-1eddbfbb74d7.png)
