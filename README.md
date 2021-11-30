# CSL7510_End_term_project

## Problem Statement

TICK stack is becoming popular for analyzing time-series IoT data. You can refer to the following link for the local machine and VM deployment of TICK stack: 
https://medium.com/codingtown/influxdb-tick-stack-part1-28bd04d10a18

As part of this project, you are expected to implement TICK stack in a dockerized environment. Each component of the TICK stack should be deployed as individual docker containers (you can also use official docker images from docker hub). Your dockerized deployment should be secure.

Submissions: A google doc file containing: 

      1. Team information
      2. Link to the source code repository 
      3. Stepwise description 
      4. List of all security measures implemented 
      5. Contribution by each team member 
      6. Link to a youtube video demonstrating the working of TICK stack in a dockerized environment 
      7. References 

Team Members :
    
    1. Shantam Saxena - M20AIE302
    2. Deepali Nikam  -  M20AIE230


How to start the application:

  Requirements:

    1. Docker installed on the system
    2. Python 3.x installed 
    3. Firewall disabled if already enavbled.
 
 Steps to start the application:

  1. open terminal/powershell in the repository directory.
  2. After chekcing if the user is in the same working directory, run:
    
    docker-compose up
 
 To access Chronograpgh : ```http://localhost:8888/```
 
 This will launch the chronograph console and the application is up and running.
 
 This repository also contains the report which has the details for every component of the TICK stack.
