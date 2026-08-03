# Microservices-Task

## Overview
This document provides details on testing various services after running the `docker-compose` file. These services include User, Product, Order, and Gateway Services. Each service has its own endpoints for testing purposes.

---

## Services and Endpoints

### **User Service**
- **Base URL:** `http://localhost:3000`
- **Endpoints:**
  - **List Users:**  
    ```
    curl http://localhost:3000/users
    ```
    Or open in your browser: [http://localhost:3000/users](http://localhost:3000/users)

---

### **Product Service**
- **Base URL:** `http://localhost:3001`
- **Endpoints:**
  - **List Products:**  
    ```
    curl http://localhost:3001/products
    ```
    Or open in your browser: [http://localhost:3001/products](http://localhost:3001/products)

---

### **Order Service**
- **Base URL:** `http://localhost:3002`
- **Endpoints:**
  - **List Orders:**  
    ```
    curl http://localhost:3002/orders
    ```
    Or open in your browser: [http://localhost:3002/orders](http://localhost:3002/orders)

---

### **Gateway Service**
- **Base URL:** `http://localhost:3003/api`
- **Endpoints:**
  - **Users:**  
    ```
    curl http://localhost:3003/api/users
    ```
  - **Products:**  
    ```
    curl http://localhost:3003/api/products
    ```
  - **Orders:**  
    ```
    curl http://localhost:3003/api/orders
    ```

---

## Instructions
1. Start all services using the `docker-compose` file:
   ```
   docker-compose up
   ```
2. Once the services are running, use the above endpoints to verify the functionality.

Happy testing!


Github repo: https://github.com/ahamedkhany/Microservices-Task.git 

 

git clone https://github.com/ahamedkhany/Microservices-Task.git 

 

Go inside local directory open command prompt using cmd and run the below command to open VS code. 

code . 

 

Add Dockerfile in all the 4 services. 

 

Add docker-compose.yml file to run multiple containers under Docker network 

 

Run the below commands 

docker compose up –build 

 

Now test the services by running in localhost 

  

 

 

Find the below screenshots for all the 4 services 

 

 

 

 

 

 

 

User-service 

 

 

Products-service 

 

 

 

 

 

Order-service 

 

 

 

Gateway-servce 

 
Since it’s gateway service you can hit urls with /api/users, /api/orders, /api/products  

 

 

 

 

 

 

 

 

 

 
