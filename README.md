# Spring Boot Search REST API

This is a simple Spring Boot application that provides a REST API for searching products in real time.

## Technologies Used

- Java
- Spring Boot
- JPA/Hibernate
- Lombok
- Maven

## Features

- Search for products by name or description.
- Create new products.

## Setup

1. Clone the repository.
2. Open the project in your favorite IDE (preferably IntelliJ IDEA).
3. Make sure you have Maven and Java installed on your machine.
4. Run the `SpringbootSearchRestApiApplication` main class to start the application.

## API Endpoints

- `GET /api/v1/products/search?query={query}`: Search for products by name or description.
- `POST /api/v1/products`: Create a new product.

## Example JSON for POST request

```json
{
    "sku": "12345",
    "name": "Product Test",
    "description": "This is a test product",
    "active": true,
    "imageUrl": "http://example.com/image.jpg"
}
