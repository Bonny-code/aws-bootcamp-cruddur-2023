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
