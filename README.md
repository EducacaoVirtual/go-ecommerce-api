# Educação Virtual - Complete Go REST API
## E-commerce Products

[![Go Reference](https://pkg.go.dev/badge/golang.org/x/example.svg)](https://pkg.go.dev/golang.org/x/example)

## Key Features

- Full CRUD operations (Create, Read, Update and Delete)
- PostgreSQL database integration with connection pooling
- Proper error handling and validation
- CORS support for frontend integration
- Health check endpoints
- Docker containerization with multi-stage builds
- Docker Compose for easy Deployment

## What's included

- **Project Setup** - Directory structure and Go module initialization
- **Configuration Management** - Environment-based config handling
- **Database Layer** - PostgreSQL connection and table creation
- **Product Model** - Structured data models with validation
- **HTTP Handlers** - Complete REST API endpoints
- **Main Application** - Server setup with routing and middleware
- **Docker Configuration** - Dockerfile and docker-compose.yml
- **Testing Commands** - curl examples for all endpoints

## API endpoints

- **GET** /api/v1/products - List all products
- **GET** /api/v1/products/{id} - Get specific product
- **POST** /api/v1/products - Create new product
- **PUT** /api/v1/products/{id} - Update product
- **DELETE** /api/v1/products/{id} - Delete product
- **GET** /health - Health check