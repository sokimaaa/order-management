# Order Management

## Objective

The objective of this project is to design and implement
a Spring Boot Application for order administration
that is optimized for both read and write operations.
This project aims to create a non-compromise solution
where the database ensures high availability and data consistency.
The system will leverage asynchronous communication with outstanding
components for enhanced performance and reliability.

The key functionality:
- Placing order
- Notification mechanism (on order place, update, cancel and so on)
- Modification mechanism (e.g. shipping address, payment method, product list while status allows)
- Cancelling order
- Tracking order (order status, delivery status, payment status)
- Exploring order history
- Interacting through events with Inventory, Shipping, Payment services

## Technology Stack

- Java 17
- Spring Boot 3
- Project Reactor
- Apache Kafka
- R2DBC
- Postgres
- Testcontainers
- Maven
- Docker

## Architecture Perspective

Hexagonal Architecture
Command Query Responsibility Segregation (CQRS)
Master-slave

## ER Diagram

## Build & Run
