## Educação Virtual - Complete Go REST API
## E-commerce Products

[![code-style](https://github.com/cable8mm/water-melon/actions/workflows/code-style.yml/badge.svg)](https://github.com/EducacaoVirtual/)
[![run-tests](https://github.com/cable8mm/water-melon/actions/workflows/run-tests.yml/badge.svg)](https://github.com/EducacaoVirtual/)
[![Go Reference](https://pkg.go.dev/badge/golang.org/x/example.svg)](https://pkg.go.dev/golang.org/x/example)
![Packagist License](https://img.shields.io/packagist/l/cable8mm/water-melon)
<a href="https://github.com/EducacaoVirtual/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/EducacaoVirtual/go-ecommerce-api" alt="contributors" />
</a>
<a href="">
    <img src="https://img.shields.io/github/last-commit/EducacaoVirtual/go-ecommerce-api" alt="last update" />
</a>
<a href="https://github.com/EducacaoVirtual/network/members">
    <img src="https://img.shields.io/github/forks/EducacaoVirtual/go-ecommerce-api" alt="forks" />
</a>
<a href="https://github.com/EducacaoVirtual/stargazers">
    <img src="https://img.shields.io/github/stars/EducacaoVirtual/go-ecommerce-api" alt="stars" />
</a>
<a href="https://github.com/EducacaoVirtual/issues/">
    <img src="https://img.shields.io/github/issues/EducacaoVirtual/go-ecommerce-api" alt="open issues" />
</a>

## Clone Project

```sh
$ git clone https://github.com/EducacaoVirtual/
$ go-ecommerce-api.git
$ cd ecommerce-api
```

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