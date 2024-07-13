# E-commerce-Evolution-Unleashing-the-Potential-of-Serverless-Microservices

E-commerce websites have become integral to modern retail, with their architecture crucial for ensuring scalability, security, and seamless user experiences. To esure that we have developed an serverless microservices architecture in aws. Traditional monolithic architectures struggle with scaling, fault tolerance, and independent service deployments. We have created 3 different microservices product, basket and ordering microservices. The communication between users and microservices are synchronous communication. The communication between basket and ordering microservice is asynchronous communication.

<img width="731" alt="image" src="https://github.com/user-attachments/assets/69dd54fa-1602-46bd-9b65-715155a0a5d1">

If you think why serverless what is the use of it then what serverless helps you to focus on Build and run applications without thinking about
servers - running code, managing data, and integrating applications, all without managing servers. The key benifit of this is Automatic scaling, built-in high availability, and a pay-for-use billing model to increase agility and optimize costs.

The project aims to address the challenge of building a scalable, resilient, and event driven e-commerce application architecture. The project is developed in AWS CDK. The created communications between the microservices and the users we used lambda functions and api gateway. The api calls has been tested using the postman application.

<img width="846" alt="image" src="https://github.com/user-attachments/assets/13d89109-3718-4e5b-9dea-8c95ed8c1dd1">

<img width="832" alt="image" src="https://github.com/user-attachments/assets/c18cc376-c0a1-4bf7-a4c7-632356ac011a">

Prerequisites:
1. AWS free-tier account
2. AWS Command Line Interface (CLI)
3. NodeJS
4. AWS CDK Toolkit
5. Visual Studio Code
6. Docker Desktop (For Bundling Lambda Function with Libraries)
7. Postman (For Test and Manage ApiGateway Apis).

Just upload the files of lib and src to your cdk environment workspace and then follow the below steps,
To run this project you have to install all the prerequisites mentioned above and in vscode the folder structure will be created. The development will be done in src and lib folders. Simply upload the files from the src and lib folder to your workspace in vscode and type these commands:
cdk synth (Keep the docker running)
cdk deploy

A stack will be created in aws with the architecture deployed in aws. To avoid billing I recommend you to use the command cdk destroy to
destroy all the created services in aws after using them.

Thank you.
Any queries contact abhilashveluru4@gmail.com
