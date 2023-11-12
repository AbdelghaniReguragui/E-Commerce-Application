# E-Commerce-Application
It is a microservices application with 4 services:
- Catalog Service with mongoDB
- Basket service with Redis
- Discount service with PostgreSQL
- Ordering service with SQL server
Each microservice we implemente the Domain Driven Design approach with CQRS pattern  

The services are managing by a gateway api that is implementing with Ocelot
In the maeantime we use:
- RabbitMQ to intercommunicate between our services
- Docker to build, test, and deploy our application
