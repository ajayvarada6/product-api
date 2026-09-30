# Product API

Simple REST Product API built using Python Flask and Docker.

## Endpoints

GET /health

GET /products

POST /products

PUT /products/<id>

DELETE /products/<id>

## Run with Docker

docker build -t product-api .

docker run -p 8080:8080 product-api