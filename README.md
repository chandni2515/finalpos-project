# Eshop(Cart) Backend

A simple RESTful backend built with [NestJS](https://nestjs.com/) for managing products and shopping carts. These APIs allow users to create products, manage stock, and perform shopping cart operations.

## Features

- CRUD for products (name, description, image, price, stock)
- CRUD for shopping carts
- Add, update, or remove products in the cart (with stock updates)
- Swagger API docs at `/api`
- Docker support for easy setup

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Start The Application
Dev mode
```bash
npm run start:dev
```
OR Docker Compose
```bash
docker-compose up --build
```

The app will start on http://localhost:3000.

### 3. API Documentation
Swagger is available at http://localhost:3000/api

### 4. Environment
- Node.js 18+
- PostgreSQL (via Docker Compose)

Scripts
- npm run start - start normally
- npm run start:dev - start in dev/watch mode
- npm run test - run unit tests

 ## Author
- Chandni Patel
- https://github.com/chandni2515