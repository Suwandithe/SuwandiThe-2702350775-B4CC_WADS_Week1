# Web Application Development and Security

**Name:** Suwandi The
**Student ID:** 2702350775  
**Class:** B4CC

# Microservices Architecture

# What are Microservices?

Microservices are an architectural approach to developing software application as a collection of independent services that communicate with each other over a network. It breaks down the application into smaller coupled services, instead of building a monolithic application where all functionality is tightly intregated into a single codebase.

![image1](https://github.com/Suwandithe/SuwandiThe-2702350775-B4CC-WADS_Week1/blob/main/microservices1.jpeg)

Microservice is a small, loosely coupled service that is designed to perform a specific business function and each microservice can be developed, deployed, and scaled independently.

![image2](https://github.com/Suwandithe/SuwandiThe-2702350775-B4CC-WADS_Week1/blob/main/microservices2.jpeg)

- This architecture allow you to take a large monolith application and decompose it into small manageable components/services. Also, it is considered as the building block of modern applications.

- Microservices can be written in a variety of programming languages, and frameworks, and each service acts as a mini-application on its own.

# How do Microservices work?

Microservices break complex applications into smaller, independent services that work together, enhancing scalability, and maintenance. Below is how microservixes work:

- Applications are divided into self-contained services, each focused on a specific function, simplifying development and maintenance.

- Each microservice handles a particular business feature, like user authentication or product management, allowing for specialized development.

- Services interact via APIs, facilitating standardized information exchange and integration.

- Different technologies can be used for each service, enabling teams to select the best tools for their needs.

- Microservices can be updated independently, reducing risks during changes and enhancing system resilience.

# What are the main components of Microservices Architecture?

Main components of microservices architecture include:

- Microservices: Small, loosely coupled services that handle specific business functions, each focusing on a distinct capability.

- API Gateway: Acts as a central entry point for external clients also they manage requests, authentication and route the requests to the appropriate microservice.

- Service Registry and Discovery: Keeps track of the locations and addresses of all microservices, enabling them to locate and communicate with each other dynamically.

- Load Balancer: Distributes incoming traffic across multiple service instances and prevent any of the microservice from being overwhelmed.

- Containerization: Docker encapsulate microservices and their dependencies and orchestration tools like Kubernetes manage their deployment and scaling.

- Event Bus/Message Broker: Facilitates communication between microservices, allowing pub/sub asynchronous interaction of events between components/microservices.

- Database per Microservice: Each microservice usually has its own database, promoting data autonomy and allowing for independent management and scaling.

- Caching: Cache stores frequently accessed data close to the microservice which improved performance by reducing the repetitive queries.


- Fault Tolerance and Resilience Components: Components like circuit breakers and retry mechanisms ensure that the system can handle failures gracefully, maintaining overall functionality.

this is coming from experiment branch