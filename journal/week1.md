# Week 1 — App Containerization
This week was all about learning how to use Docker. I started by creating a dockerfile and copied the instructions into it, i then ran the file and open the ports making them public but i got a 404 error. However, when i append to the URL /api/activities/home i got some json data which means it's working.
         I ran npm install for both Frontend and Backend and then created the docker-compose.yml file and added some content into it. After that i used docker-compose to launch the containers and opened the ports so i could see the application on my browser.
       I added a notification endpoint using OpenApi, after which i added a a page for notifications using React in the application frontend. After installing aws cli, i was able to use it and configure dynamodb and same with postgres.
        Attached below is my docker-compose file.yml
        ![2023-03-01 (5)](https://user-images.githubusercontent.com/75304701/222241670-247ef5e5-2de4-44dc-bb97-a31c9893e567.png)
        below is my gitpod.yml file![2023-03-01 (6)](https://user-images.githubusercontent.com/75304701/222242288-c1461e72-ccf2-4e97-911b-010c8ee62343.png)
        Docker images running
        ![2023-03-01 (7)](https://user-images.githubusercontent.com/75304701/222242672-9c8017ef-fd0e-49c5-8143-b5af055668d5.png)



