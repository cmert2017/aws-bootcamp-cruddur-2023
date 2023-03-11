# Week 1 — App Containerization

## Required homeworks  

## 1- I finished all the required homeworks and below is the related commits:  
source: https://github.com/cmert2017/aws-bootcamp-cruddur-2023/commits/main  
<img width="1395" alt="image" src="https://user-images.githubusercontent.com/25131600/221443190-b9991f6d-a6c4-43d5-854f-59738ab5b25f.png">
  
## 2- Dynamodb  chanllange is done.  
  <img width="1430" alt="image" src="https://user-images.githubusercontent.com/25131600/221444481-4dd60587-c8ee-4253-8f75-47d5cdce88a5.png">  
  
## 3- Using Postgres in the app  
<img width="1432" alt="image" src="https://user-images.githubusercontent.com/25131600/221444590-a533560e-3631-41b6-baa2-0021de71c418.png">  

## 4- Added the notification feature  
<img width="1356" alt="image" src="https://user-images.githubusercontent.com/25131600/221455125-912b6d10-de96-4f18-a6df-152d2b4fc893.png">  

## Homework Challanges 

## 1- Learned how to install Docker on my local machine and got the same containers running outside of Gitpod / Codespaces  
Note: I had here several challanges: **First**: in my local, frontend-flask didnt run and after debugging I saw that npm install directory was not correct and after updating it, I delete my docker in docker dashboard and then rerun the docker compose up, it worked. As seen below.  
<img width="1438" alt="Screenshot 2023-02-26 at 21 43 49" src="https://user-images.githubusercontent.com/25131600/221464219-9da00877-4b96-4e5e-89a3-40cb10218497.png">  
<img width="1438" alt="Screenshot 2023-02-26 at 21 52 55" src="https://user-images.githubusercontent.com/25131600/221464235-e90282fb-ac83-477a-8fb8-4d964129786c.png">  

**Second**: When i open the front end in the browser it didnt show the icons as seen below.  

<img width="1432" alt="image" src="https://user-images.githubusercontent.com/25131600/221464338-7eeb824e-dc5a-434b-a4d4-09e13d939990.png">  

 **Then** after debugging, I noticed that URL's were not correct for localhost and I changed them as seen below.  
 <img width="1278" alt="image" src="https://user-images.githubusercontent.com/25131600/221752221-6f957729-c65d-4a5a-9541-a2166f048ac4.png">  
 
 **Then** this time it didnt show the icons. After debugging I founf that loaddata was missing. After adding it finally it worked.  
 <img width="1285" alt="image" src="https://user-images.githubusercontent.com/25131600/221752379-3ed4d02d-65e4-40ee-84d1-700b427645da.png">  
 <img width="1352" alt="image" src="https://user-images.githubusercontent.com/25131600/221752428-01028875-82d9-4c26-91bf-bbfcdd44a425.png">  
 
 ## 2- I ran both frontend and backend dockerfile's CMD as an external script  
 <img width="1281" alt="image" src="https://user-images.githubusercontent.com/25131600/221757649-ce912204-95b1-4fd0-ba19-2e6086742b92.png">  
 here is the commit for this: https://github.com/cmert2017/aws-bootcamp-cruddur-2023/commit/821e8b56183edfe2d2699d3915b17bb82800d8b8  
 
 ## 3- Implement a healthcheck in the V3 Docker compose file  
 
<img width="1290" alt="image" src="https://user-images.githubusercontent.com/25131600/221971795-9b425e60-d720-4c56-ae88-2d40ab8a4b56.png">
 
## 4- Pushed and tagged a image to DockerHub

<img width="1287" alt="image" src="https://user-images.githubusercontent.com/25131600/221977813-90d40517-eedd-4eb7-ba13-e401bfa5798b.png">  
<img width="1429" alt="image" src="https://user-images.githubusercontent.com/25131600/221978028-e688b6a1-e588-4c65-bdb2-1e71a4bfdb59.png">  

## 5- Launch an EC2 instance that has docker installed, and pull a container to demonstrate you can run your own docker processes.  
<img width="1403" alt="image" src="https://user-images.githubusercontent.com/25131600/222309670-795736a0-8168-4bff-adf4-ed012922b101.png">  
<img width="1208" alt="image" src="https://user-images.githubusercontent.com/25131600/222309755-d015b053-a8f0-4131-9f3e-4fb6dc7f2821.png">
