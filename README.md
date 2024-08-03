# internship-I

# Internship Projects

## Overview

During my six-month internship, I worked on two major projects that involved developing applications for CA generation, authentication, and blockchain integration. Below is a detailed explanation of each project.

---

## Project 1: PKI Architecture and Authentication System

### Description

This project involved the implementation of a PKI architecture based on the open source EJBCA solution. Additionally, we implemented a robust authentication system using Keycloak.

### Technologies Used

- **Backend**: NestJS
- **Frontend**: Next.js
- **Authentication**: Keycloak
- **PKI**: EJBCA

### Features

1. **PKI Architecture**: Implemented a Public Key Infrastructure (PKI) based on the EJBCA solution.
2. **CA Generation**: The application allows for the generation and management of Certificate Authorities.
3. **Keycloak Integration**: Implemented Keycloak for secure authentication and authorization.
4. **User Management**: Managed user roles and permissions through Keycloak.
5. **Documentation**: Comprehensive documentation to guide users on how to use the application.

---
## Project 2: Blockchain Timestamping System

### Description

The second project focused on creating a backend system that communicates with a smart contract to store and retrieve data from the blockchain. The system handles multiple requests using RabbitMQ and sends responses back to a frontend. Additionally, an open API was developed for developers to interact with the blockchain system.

### Technologies Used

- **Backend**: NestJS
- **Frontend**: Next.js
- **Message Queuing**: RabbitMQ
- **Blockchain**: Smart contracts for data storage and retrieval

### Features

1. **Data Storage and Retrieval**: Interacted with smart contracts to store and retrieve data from the blockchain.
2. **Handling Multiple Requests**: Utilized RabbitMQ to handle multiple concurrent requests efficiently.
3. **Open API**: Developed an API for developers to store data in the blockchain and check the status of their data.
   - **API Key Management**: Implemented mechanisms to generate, revoke, and rotate API keys through an admin panel.
   - **API Key Validation**: Added a customized controller to check the status of API keys, including creation date, expiration date, and remaining requests.
4. **API Documentation**: 
   - **User Guide**: Wrote detailed documentation explaining the usage of the API.
   - **Swagger Documentation**: Integrated Swagger to help developers understand and use the API effectively.

### Key Components

- **Frontend**: Developed a user-friendly frontend using Next.js to interact with the backend system.
- **Backend**: Built a robust backend using NestJS to handle business logic and communicate with the blockchain.
- **Message Queuing**: Implemented RabbitMQ to manage multiple requests and ensure reliable message delivery.

---

## Conclusion

Throughout my internship, I gained valuable experience in backend and frontend development, authentication systems, blockchain technology, and Web3 development. The projects allowed me to enhance my skills in NestJS, Next.js, RabbitMQ, Keycloak, and blockchain integration, as well as develop comprehensive documentation for APIs.

---

## Contact

For any queries or further information, please feel free to contact me at youssef.elaouny1010@gmail.com .
