# Week 3 — Decentralized Authentication

This week was all about decentralised authentication using amazon cognito and amplify. I started by watching the first live video and was able to install and save aws amplify.
I continued by going into the console and creating a user pool with aws cognito name cruddur-user-pool.![2023-03-07 (2)](https://user-images.githubusercontent.com/75304701/223380323-f920109b-ec57-4ade-a22c-39fabe213a17.png)
Then i implemented some changes in the code's dockoer-compose file, app.js, SigninPage.js, HomeFeed.js and others.
I also created a user called bonise in my cognito user pool![2023-03-07 (1)](https://user-images.githubusercontent.com/75304701/223380969-7c2b611d-250e-47f7-9dd2-38ef14d989c2.png)
After which i tried logging into my app but got the "cannot read properties error" as shown below![2023-03-07](https://user-images.githubusercontent.com/75304701/223381300-88ac807f-b329-4a01-b050-e1c69c315639.png)

I finally impemented changes to my custom page and used aws cli to set the credentials 
![2023-03-07 (3)](https://user-images.githubusercontent.com/75304701/223389695-510e90c9-ca0e-4949-8c0e-b2d1bbcc64f3.png)

and i was finally able to log into the app with the above credentails 
![2023-03-07 (4)](https://user-images.githubusercontent.com/75304701/223389892-0a90a6d7-9447-41dc-ae58-161131000838.png)

and i was able to log in with my name and usernam showing

![2023-03-07 (5)](https://user-images.githubusercontent.com/75304701/223635400-81c0b868-b343-4d61-91a3-0dc436a8cd86.png)

I was able to sign up and made it to the confimation page as shown below
![2023-03-08](https://user-images.githubusercontent.com/75304701/223847556-930c25b5-d194-4096-a212-2bab4945c26a.png)

here we have the unconfirmed user

![2023-03-08 (1)](https://user-images.githubusercontent.com/75304701/223847866-aafb59cb-8101-49da-a1db-efd790eb0d39.png)

I was able to recieve a verification email as hsown below
![2023-03-08 (2)](https://user-images.githubusercontent.com/75304701/223848077-f99bc6eb-7f40-4e03-938d-385f5d65eca9.png)

After using the verification code, the user was finally confirmed as shown below
![2023-03-08 (3)](https://user-images.githubusercontent.com/75304701/223848418-e1987bb9-069a-46d1-89f7-1b6cf031ed75.png)

One of the major challenges i faced was in implementing jwt token, i was not able to get the authentication message in the terminal since my backend port was not beign served so i had to try and debug it.




