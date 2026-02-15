# GearHead Microservices Platform – Portfolio

This repository serves as the **central portfolio** for the GearHead Microservices Platform.  
It links all backend microservices and frontend applications, showing the full system architecture in one place.

---

## Architecture Overview

The GearHead platform is a full-stack microservices system with:

- API Gateway as a single entry point  
- Centralized configuration server  
- Independent backend services (business logic, products, identity)  
- Front-end applications for admin and users  
- Scalable and maintainable distributed architecture  

---

## Backend Microservices

| Service | Description | Repository |
|---------|-------------|------------|
| Identity Service | Handles authentication and authorization | [identity_service](https://github.com/SnaxKillau/identity_service) |
| Config Server | Centralized configuration for all services | [gearhead_config](https://github.com/SnaxKillau/gearhead_config) |
| API Gateway | Single entry point that routes requests to backend services | [gearhead_gatewayserver](https://github.com/SnaxKillau/gearhead_gatewayserver) |
| Main Backend Server | Core business logic and application services | [gearheadserver](https://github.com/SnaxKillau/gearheadserver) |
| Product Service | Handles product management and related operations | [gearhead_product](https://github.com/SnaxKillau/gearhead_product) |

---

## Frontend Applications

| Frontend | Description | Repository |
|----------|-------------|------------|
| Dashboard | Admin panel for managing the system | [gearhead_dashbord](https://github.com/SnaxKillau/gearhead_dashbord) |
| User Frontend | Customer-facing application | [gearhead-font-end](https://github.com/SnaxKillau/gearhead-font-end) |

---

## Key Features

- Microservices architecture using Spring Boot and Spring Cloud  
- API Gateway routing  
- Centralized configuration management  
- Authentication & authorization  
- Independent services for scalability  
- Separate admin and user interfaces  

---

## How to Run (Example Flow)

1. Start Config Server  
2. Start Identity Service  
3. Start Gateway Server  
4. Start Backend Services (Main Backend, Product Service)  
5. Run Frontend Applications  

---

## Purpose

This repository is designed for:

- Demonstrating real-world microservices architecture  
- Showcasing full-stack backend and frontend development  
- Portfolio/CV purposes  
- Learning distributed systems design  

---

## Author

SnaxKillau  

---

**CV Example:**  

