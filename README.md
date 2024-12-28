# Dockerized-bookstore-api

A containerized bookstore API demonstrating modern application deployment using Docker, Terraform, and AWS cloud infrastructure.

## Project Highlights

✨ Automated cloud infrastructure deployment with Terraform  
✨ Containerized application using Docker and Docker Compose  
✨ RESTful API with database integration  
✨ Infrastructure as Code implementation

## Key Features

• Cloud Automation
  - Infrastructure as Code with Terraform
  - Automated AWS resource provisioning
  - Container orchestration with Docker Compose

• Application Design
  - RESTful API architecture
  - Containerized services
  - Persistent data storage

• Development Practices
  - Microservices approach
  - Infrastructure automation
  - Container-based deployment


## Quick Start

1. **Setup Infrastructure**
   ```bash
   # Initialize Terraform
   terraform init

   # Deploy infrastructure
   terraform apply
   ```

2. **Access API**
   ```bash
   # Get books
   curl http://[ec2-hostname]/books

   # Add book
   curl -X POST http://[ec2-hostname]/books
   ```

3. **API Endpoints**
   - List all books: GET `/books`
   - Get specific book: GET `/books/123`
   - Create book: POST `/books`
   - Update book: PUT `/books/123`
   - Delete book: DELETE `/books/123`
