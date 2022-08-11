# DASDS
Driver automobile and safety detection system [First place STEM competition]

## System Environments
Our system will be implemented in modern cars. It will make use of cameras and OBD II to guarantee the drivers safety. We will require 2 cameras for: 

1- OCR detection of license for guest users  
2- Detecting facial motions for sleepy or distracted drivers 
3- Detection of drunk drivers using MQ3 sensor 
![SystemEnv-dasds](https://user-images.githubusercontent.com/69352154/184198356-41f745b4-e6bc-4deb-a02a-95de5d42f68b.jpg)

## System Sequence Diagrams
Logging in and authentication
![systemDesign1](https://user-images.githubusercontent.com/69352154/184198840-583d9a20-c92e-454f-9090-048f817b81aa.png)


Driver under the influence detection
![systemDesign2](https://user-images.githubusercontent.com/69352154/184199007-ef373e9a-609e-4136-b3b9-8d543d099d88.png)

Distracted driver detection
![systemDesign3](https://user-images.githubusercontent.com/69352154/184199148-230ffb08-4309-483a-8da4-31a94a29d80f.png)


## System Architecture 

System Architectures are an essential part of developing and maintaining systems primarily because they are like blueprints of a software. 
![systemDesign4](https://user-images.githubusercontent.com/69352154/184199737-52a8ec74-fa91-4475-873c-922bcfcec81c.png)


![image](https://user-images.githubusercontent.com/69352154/184196918-dac4832a-a301-40a6-862d-58520d8752d8.png)

## Deployment Architecture 

The Deployment Diagram is used to depict the running environment of the system. The Mobile Application will be an Android Application, developed using a java framework known as Koltin. Our Application Programming Interface (API) will be developed using Node.js. Moving on, our Database Instance will be of MongoDB which is in JSON format this will be linked with our API using a Node.js local server on the raspberry pi. We will be using Python to develop our neural networks and machine learning models.

![systemDesign5](https://user-images.githubusercontent.com/69352154/184237360-6ff101f4-b8c6-45db-827a-6037dc67bb45.png)

### fin

