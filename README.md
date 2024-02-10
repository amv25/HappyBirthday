# HappyBirthday

Technologies:
Oracle
Java 8
Spring boot
Spring security
OAuth
React
GitLab CI/CD / Jenkins
Docker
AWS - EC2, Lambda, AWS RDS / AWS AURORA
Kubernetes

Desc:
This prject sends reminder mail on your friends' birthday

Project:
1. create database with name, date and Gift
2. Create a login for user using spring security and auth0
3. set a scheduler that checks the DB for birthdays at 12am
4. set up another scheduler to send a remainder to buy the gift if present in the DB 
5. Integrate it with an external mail client to send mail
6. set up a pipeline using gitlab CI/CD or Jenkins to run maven clean install, create a docker image and deploy the docker image in AWS EC2
7. Deploy the database in AWS RDS or create a database in AWS Aurora and connect to it
8. Use postman

Additional:
1. Create front-end in React
2. Create a separate endpoint to get data for populating the UI screen
3. Implement loadbalancing in ECS or EKS and kubernetes
4. implement database and integration with noSQL or dynamoDB



