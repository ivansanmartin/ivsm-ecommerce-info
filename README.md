# ivsm-ecommerce - `IN DEVELOPMENT` | `EN DESARROLLO`

ivsm-ecommerce is an e-commerce marketplace I'm developing as a practice project to apply different technologies.

# Features

+ E-commerce platform: A fully functional e-commerce platform for buying and selling products.

+ Chat support: Live chat support for customers to communicate with the team.

+ Administrative panel: A dedicated administrative panel for managing the store, products, orders, and users.

+ Team permission rules: Granular permission rules for team members to control access to different functionalities in admin panel.

+ Google integration: Integration with Google for user authentication and registration.

+ Multiple payment methods: Support for multiple payment gateways, including WebPay and MercadoPago.

+ Separation of e-commerce and admin: Clear separation between the e-commerce storefront and the administrative panel.

+ Docker development: Development using Docker containers for a consistent and reproducible development environment.

+ Kubernetes orchestration in production: Orchestration with Kubernetes for managing and scaling the application in production.

# Architecture

The ivsm-ecommerce project follows a microservices architecture, where different components are organized into separate services. This architecture promotes modularity, scalability, and maintainability of the application. The main microservices in this project are:

+ ivsm-ecommerce-client: Frontend client application.
  
  + Repository: [Click Here](https://github.com/ivansanmartin/ivsm-ecommerce-client)

+ ivsm-ecommerce-server: Backend server for handling business logic and data.
  
  + Repository: [Click Here](https://github.com/ivansanmartin/ivsm-ecommerce-server)
    
+ ivsm-ecommerce-panel: Admin panel for managing the store, products, orders, and users.
  
  + Repository: [Click Here](https://github.com/ivansanmartin/ivsm-ecommerce-panel)

This approach allows for independent development, deployment, and scaling of each service, providing flexibility and agility in the development process.

# Technologies

## DBMS:

+ PostgreSQL: Employed as the main relational database managed with pgAdmin.
+ MongoDB: Utilized for NoSQL data storage, managed with MongoDB Compass.
+ Redis: Used for caching purposes, managed with The Another Redis Desktop.
  
## Development Tools

+ Backend Framework: NestJS.
+ Client Framework: Astro.
+ Admin Panel Framework: Currently under selection.
  
This technology stack forms the backbone of the ivsm-ecommerce project, providing robustness, scalability, and flexibility throughout development and deployment processes.

# Development and Deployment

## Docker Development

Docker is utilized for local development, ensuring a consistent and reproducible environment across different development machines. Docker simplifies dependency management, making development workflows smoother.

## Kubernetes Orchestration in Production

For production deployment, Kubernetes is relied upon. Kubernetes enables efficient management of scalability, deployment, and resources in the production environment. This ensures high availability and reliability for the ivsm-ecommerce platform, meeting the demands of modern e-commerce applications.
  
# E-COMMERCE \ Database normalization (1FN | 2FN | 3FN)

[adminpanel-normalization-db.xlsx](https://github.com/ivansanmartin/ivsm-ecommerce/files/14547849/adminpanel-normalization-db.xlsx)


Preview:

![preview-ecommerce-normalization-db](https://github.com/ivansanmartin/ivsm-ecommerce/assets/54847509/720a4647-da3c-4105-8c38-7e613f5b6af0)


# E-COMMERCE \ Relational Diagram of Database

![ecommerce-relational-model-db](https://github.com/ivansanmartin/ivsm-ecommerce/assets/54847509/7326ae77-cd5d-4dad-9514-fa859edbb13c)

## E-COMMERCE \ DDL 

This is the dedicated DDL for creating all the necessary tables for the ivsm-ecommerce project `(THIS DDL MAY CHANGE, REMEMBER THAT IT IS UNDER DEVELOPMENT)`

[![gists-readme](https://gists-readme.yizack.com/api/pin?user=&id=775cc2beea79aa07809f388422bbf6b7&owner=true&theme=dark)](https://gist.github.com/ivansanmartin/775cc2beea79aa07809f388422bbf6b7)


# ADMIN-PANEL \ Database Normalization (1FN | 2FN | 3FN)

[ecommerce-normalization-db.xlsx](https://github.com/ivansanmartin/ivsm-ecommerce/files/14547850/ecommerce-normalization-db.xlsx)


Preview:

![preview-adminpanel-normalization-db](https://github.com/ivansanmartin/ivsm-ecommerce/assets/54847509/90e871cb-4ee7-400b-80db-680dc6dab0b6)


# ADMIN-PANEL \ Relational Diagram of Database

![adminpanel-relational-model-db](https://github.com/ivansanmartin/ivsm-ecommerce/assets/54847509/03badec4-64ee-4b1f-9519-3d40d0a38559)

## ADMIN-PANEL \ DDL

This is the dedicated DDL for creating all the necessary tables for the ivsm-ecommerce administrative panel `(THIS DDL MAY CHANGE, REMEMBER THAT IT IS UNDER DEVELOPMENT)`

[![gists-readme](https://gists-readme.yizack.com/api/pin?user=&id=9da40b46b7160c8383db756842d4114a&owner=true&theme=dark)](https://gists-readme.yizack.com/api/pin?user=&id=9da40b46b7160c8383db756842d4114a&owner=true&theme=dark)








