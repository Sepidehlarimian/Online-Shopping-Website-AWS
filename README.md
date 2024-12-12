# E-SHOPPER: Scalable Cloud-Based Online Shopping Platform

E-SHOPPER is an online shopping website designed to solve the challenges of handling high traffic during peak events, such as "Black Friday." The platform leverages AWS cloud infrastructure to enhance scalability, responsiveness, and overall user experience. 

## Problem Addressed
Traditional shopping websites often fail to handle high user traffic, leading to poor customer experiences and lost revenue. This project addresses this issue by implementing a scalable and efficient architecture using AWS services.

## Features
- **Catalog, Cart, and Payment System**: Complete e-commerce functionality with user profiles and management.
- **Cloud-Based Architecture**: Utilizes AWS services like EC2, RDS, and VPC for high availability and performance.
- **Load Balancing**: Dynamically handles traffic peaks using Nginx and Elastic Load Balancers.
- **Microservice Design**: Ensures modular and scalable components for critical services.
- **Secure Remote Access**: Configured key pairs and security groups for safe management.

## Technologies and Services Used
- **AWS Services**: 
  - EC2 (Elastic Compute Cloud) for hosting the web service
  - RDS (Relational Database Service) for database management
  - VPC (Virtual Private Cloud) for a secure cloud environment
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL (connected via MySQL Workbench)
- **Web Server**: Nginx
- **Source Code Management**: GitHub

## Architecture
- **Layered Design**: A landing page connects to all other services, creating a user-friendly interface.
- **Cloud-Based Database**: RDS is used to host the database, separating web server traffic from database requests.
- **Nginx Proxy**: Handles requests efficiently with load balancing and authentication capabilities.
- **Custom Virtual Network**: VPC enables isolated, secure hosting of all resources.

## Development Workflow
1. **Set Up AWS Infrastructure**:
   - Created a VPS for deploying EC2 and RDS.
   - Configured security groups for SSH, HTTP/HTTPS, and database access.
   - Generated key pairs for secure remote access.
2. **Web Server and Database Deployment**:
   - Installed and configured Nginx and PHP on an EC2 instance.
   - Deployed an RDS database and created necessary tables.
3. **Code Integration**:
   - Uploaded source code from GitHub to the EC2 instance.
   - Extracted and placed files in the Nginx directory (`/user/share/nginx/html`).
   - Configured database connection (`conn.php`) for remote RDS access.
4. **Final Testing**:
   - Tested website functionalities, including user registration, login, cart management, and order placement.

## Key Features and Benefits
- **Scalability**: Automatic scaling of EC2 instances ensures seamless performance during high traffic peaks.
- **Security**: Secure key-based authentication and segregated database architecture.
- **Efficient Load Management**: Nginx handles user requests effectively without impacting database performance.
- **Modularity**: The microservice-inspired architecture supports easy updates and maintenance.

## Future Improvements
- Enhance security by avoiding cookies for sensitive data.
- Implement caching mechanisms for improved speed.
- Extend functionality with more robust microservices.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/e-shopper.git
# E-SHOPPER: Scalable Cloud-Based Online Shopping Platform

E-SHOPPER is an online shopping website designed to solve the challenges of handling high traffic during peak events, such as "Black Friday." The platform leverages AWS cloud infrastructure to enhance scalability, responsiveness, and overall user experience. 

## Problem Addressed
Traditional shopping websites often fail to handle high user traffic, leading to poor customer experiences and lost revenue. This project addresses this issue by implementing a scalable and efficient architecture using AWS services.

## Features
- **Catalog, Cart, and Payment System**: Complete e-commerce functionality with user profiles and management.
- **Cloud-Based Architecture**: Utilizes AWS services like EC2, RDS, and VPC for high availability and performance.
- **Load Balancing**: Dynamically handles traffic peaks using Nginx and Elastic Load Balancers.
- **Microservice Design**: Ensures modular and scalable components for critical services.
- **Secure Remote Access**: Configured key pairs and security groups for safe management.

## Technologies and Services Used
- **AWS Services**: 
  - EC2 (Elastic Compute Cloud) for hosting the web service
  - RDS (Relational Database Service) for database management
  - VPC (Virtual Private Cloud) for a secure cloud environment
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL (connected via MySQL Workbench)
- **Web Server**: Nginx
- **Source Code Management**: GitHub

## Architecture
- **Layered Design**: A landing page connects to all other services, creating a user-friendly interface.
- **Cloud-Based Database**: RDS is used to host the database, separating web server traffic from database requests.
- **Nginx Proxy**: Handles requests efficiently with load balancing and authentication capabilities.
- **Custom Virtual Network**: VPC enables isolated, secure hosting of all resources.

## Development Workflow
1. **Set Up AWS Infrastructure**:
   - Created a VPS for deploying EC2 and RDS.
   - Configured security groups for SSH, HTTP/HTTPS, and database access.
   - Generated key pairs for secure remote access.
2. **Web Server and Database Deployment**:
   - Installed and configured Nginx and PHP on an EC2 instance.
   - Deployed an RDS database and created necessary tables.
3. **Code Integration**:
   - Uploaded source code from GitHub to the EC2 instance.
   - Extracted and placed files in the Nginx directory (`/user/share/nginx/html`).
   - Configured database connection (`conn.php`) for remote RDS access.
4. **Final Testing**:
   - Tested website functionalities, including user registration, login, cart management, and order placement.

## Key Features and Benefits
- **Scalability**: Automatic scaling of EC2 instances ensures seamless performance during high traffic peaks.
- **Security**: Secure key-based authentication and segregated database architecture.
- **Efficient Load Management**: Nginx handles user requests effectively without impacting database performance.
- **Modularity**: The microservice-inspired architecture supports easy updates and maintenance.

## Future Improvements
- Enhance security by avoiding cookies for sensitive data.
- Implement caching mechanisms for improved speed.
- Extend functionality with more robust microservices.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/e-shopper.git
# E-SHOPPER: Scalable Cloud-Based Online Shopping Platform

E-SHOPPER is an online shopping website designed to solve the challenges of handling high traffic during peak events, such as "Black Friday." The platform leverages AWS cloud infrastructure to enhance scalability, responsiveness, and overall user experience. 

## Problem Addressed
Traditional shopping websites often fail to handle high user traffic, leading to poor customer experiences and lost revenue. This project addresses this issue by implementing a scalable and efficient architecture using AWS services.

## Features
- **Catalog, Cart, and Payment System**: Complete e-commerce functionality with user profiles and management.
- **Cloud-Based Architecture**: Utilizes AWS services like EC2, RDS, and VPC for high availability and performance.
- **Load Balancing**: Dynamically handles traffic peaks using Nginx and Elastic Load Balancers.
- **Microservice Design**: Ensures modular and scalable components for critical services.
- **Secure Remote Access**: Configured key pairs and security groups for safe management.

## Technologies and Services Used
- **AWS Services**: 
  - EC2 (Elastic Compute Cloud) for hosting the web service
  - RDS (Relational Database Service) for database management
  - VPC (Virtual Private Cloud) for a secure cloud environment
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL (connected via MySQL Workbench)
- **Web Server**: Nginx
- **Source Code Management**: GitHub

## Architecture
- **Layered Design**: A landing page connects to all other services, creating a user-friendly interface.
- **Cloud-Based Database**: RDS is used to host the database, separating web server traffic from database requests.
- **Nginx Proxy**: Handles requests efficiently with load balancing and authentication capabilities.
- **Custom Virtual Network**: VPC enables isolated, secure hosting of all resources.

## Development Workflow
1. **Set Up AWS Infrastructure**:
   - Created a VPS for deploying EC2 and RDS.
   - Configured security groups for SSH, HTTP/HTTPS, and database access.
   - Generated key pairs for secure remote access.
2. **Web Server and Database Deployment**:
   - Installed and configured Nginx and PHP on an EC2 instance.
   - Deployed an RDS database and created necessary tables.
3. **Code Integration**:
   - Uploaded source code from GitHub to the EC2 instance.
   - Extracted and placed files in the Nginx directory (`/user/share/nginx/html`).
   - Configured database connection (`conn.php`) for remote RDS access.
4. **Final Testing**:
   - Tested website functionalities, including user registration, login, cart management, and order placement.

## Key Features and Benefits
- **Scalability**: Automatic scaling of EC2 instances ensures seamless performance during high traffic peaks.
- **Security**: Secure key-based authentication and segregated database architecture.
- **Efficient Load Management**: Nginx handles user requests effectively without impacting database performance.
- **Modularity**: The microservice-inspired architecture supports easy updates and maintenance.

## Future Improvements
- Enhance security by avoiding cookies for sensitive data.
- Implement caching mechanisms for improved speed.
- Extend functionality with more robust microservices.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/e-shopper.git
   
2. Deploy the files to an EC2 instance configured with Nginx and PHP.
3. Set up an RDS database and configure (`conn.php`) with the database credentials.
4. Access the application via the EC2 instance's public IP.
