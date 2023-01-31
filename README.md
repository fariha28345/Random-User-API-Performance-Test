# Random-User-API-Performance-Test

## Technology Used
- JMeter
- Java

## Scenerio
Find out the actual TPS for if 120000 user can give load for 12 hour
Perform load test on this URL: https://random-data-api.com/api/v2/users
1. You have to find out if the expected TPS (Transaction Per/Second) meet the above requirement.
Breakdown the expected TPS in excel sheet and find out the actual TPS
2. Create another excel sheet where you will try to find out the bottleneck/stress test point. (At which point the system starts to show 1% error)

## How to run this project
- Clone this project
- Save the .jmx file in bin folder of Apche Jmeter
- Run the .jmx file on jmeter

## Load & Stress Test Strategy
https://docs.google.com/spreadsheets/d/1KT4QQAQmU47poaMwPume3btWniNGLBXtEwBE546TphE/edit?usp=sharing

## Screenshot of Load & Stress Test Strategy Report
![Load Test](https://user-images.githubusercontent.com/50767962/215772916-5fcbfdbe-e939-4804-9552-956fdb513f5a.PNG)

![Stress_Test](https://user-images.githubusercontent.com/50767962/215775311-55b4b120-9670-4dca-a09e-ee562582dec0.PNG | width=100)
