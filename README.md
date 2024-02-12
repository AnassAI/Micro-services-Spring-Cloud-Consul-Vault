# Microservices-based Invoice Management Application

This project aims to create an application based on a microservices architecture for managing invoices that contain products and belong to a specific client. The following steps outline the implementation:

1. **Customer Service Microservice:** Create the microservice responsible for managing clients.

2. **Inventory Service Microservice:** Develop the microservice responsible for managing products.

3. **Spring Cloud Gateway:** Establish the Spring Cloud Gateway to act as a gateway for routing requests.

4. **Static Configuration of Routing System:** Configure the system for static routing to manage the flow of requests.

5. **Eureka Discovery Service:** Implement the Eureka Discovery Service to serve as a directory for service registration and discovery.

6. **Dynamic Gateway Route Configuration:** Enable dynamic configuration of routes within the gateway for flexibility.

7. **Billing Service Microservice with OpenFeign:** Create the Billing Service microservice utilizing OpenFeign for service-to-service communication.

8. **Angular Web Client:** Develop an Angular-based web client to interact with the created microservices, including functionalities for managing clients, products, and invoices.

## Additional Components:

- **Microservices Registered in Consul:**
<img src="Pics/4.png"/><br/>

- **Token in Consul:**
<img src="Pics/5.png"/><br/>

- **Token in Vault:**
<img src="Pics/6.png"/><br/>


The provided images demonstrate aspects such as microservices registration in Consul and the management of tokens in both Consul and Vault.
