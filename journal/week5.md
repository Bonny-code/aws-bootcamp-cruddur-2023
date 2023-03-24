# Week 5 — DynamoDB and Serverless Caching

This week was long and hard. I watched all the videos and learnt a lot about data modelling in dynamodb, implementing a query using single table design and also provisioning tables with provisioned capacity. I created the schema-load page and executed it. Modified a lot of the existing files to fit our dynamodb purpose. Some modifications went smoothly and others did not and gave me different results which i had to try and debug to fix them. I also watched Ashish's video and learnt about DAX and security best practices for dynamodb.

CHALLENGES
         Following the videos instructions and making the necessary changes in my application threw up a lot of errors. Some i was able to debug but others i couldn't as at now. My app was blank at some point because the MessageGroupNewPage.js was not loading but i was able to debug that.
          The major challenge this week was my that after typing messages, it could not be displayed on the screen as shown in the video. I am currently still working on trying to debug it. I sure i made an error somewhere but confident i will be able to debug it at some point. 

Looking forward to next week.

In details, i use built the schema-load page and executed the file.
Created list table and made it executable.
created messages and also modified db.py
created ddb table and activated streams
created vpc endpoint called cruddur1
created a new lambda function for cruddur-message-streams
added permissions![2023-03-24](https://user-images.githubusercontent.com/75304701/227493949-1109efbe-19fc-4178-b6bf-912e76f2eb8a.png)

created a trigger in dynamodb streams.
Below are some of the screenshots taken while doing the exercise.
![2023-03-20](https://user-images.githubusercontent.com/75304701/227495704-2e66944c-0533-4040-a384-1a8a06b45b3d.png)
![2023-03-21 (1)](https://user-images.githubusercontent.com/75304701/227495714-3de8e2ad-7244-4040-97c0-e8ce1d6d96c5.png)
![2023-03-21 (2)](https://user-images.githubusercontent.com/75304701/227495716-5fd9f1ef-0ab3-48d3-9c5d-b57748a17fca.png)
![2023-03-21 (3)](https://user-images.githubusercontent.com/75304701/227495721-86b1ade8-e4ff-447f-9b11-0e70136d03e6.png)
![2023-03-21 (4)](https://user-images.githubusercontent.com/75304701/227495725-52ff6bec-d8fe-4060-8833-5f72c93e4bd1.png)
![2023-03-21 (5)](https://user-images.githubusercontent.com/75304701/227495728-8dd6695b-f46e-400e-ae95-3370442e94b0.png)
![2023-03-21 (6)](https://user-images.githubusercontent.com/75304701/227495730-4e4b379d-e276-4a59-9017-bb420516dc2e.png)
![2023-03-21](https://user-images.githubusercontent.com/75304701/227495732-1c692fbf-4588-4219-bd69-7949acc6b8f2.png)
![2023-03-22 (1)](https://user-images.githubusercontent.com/75304701/227495735-91ad9add-f9ad-4744-81ce-e07a1ffc393b.png)
![2023-03-22](https://user-images.githubusercontent.com/75304701/227495738-04599704-e159-402e-87a7-853b4f1b3b9d.png)
![2023-03-23 (1)](https://user-images.githubusercontent.com/75304701/227495743-5bdb426f-56f4-413b-9641-c0a2a1aa6873.png)
![2023-03-23 (2)](https://user-images.githubusercontent.com/75304701/227495746-085299c0-b82f-46c3-987e-95c8341757ca.png)
![2023-03-23](https://user-images.githubusercontent.com/75304701/227495750-7ed2b525-2679-42d6-85b0-8d0ae2ae60a7.png)
![2023-03-24 (1)](https://user-images.githubusercontent.com/75304701/227495756-7a12fe7a-d580-49ef-9430-ad2ceea17469.png)
![2023-03-24 (2)](https://user-images.githubusercontent.com/75304701/227495761-0abb38ec-3568-45fc-96ad-f3ac0e1cb454.png)
![2023-03-24 (3)](https://user-images.githubusercontent.com/75304701/227495765-7e1f3e94-6b63-4b9b-b9da-fdcb30162ccc.png)
![2023-03-24](https://user-images.githubusercontent.com/75304701/227495769-98c67b16-215a-4efd-893e-70e9d4690562.png)
