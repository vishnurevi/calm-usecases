# CALM Use Cases

This repository contains simple, beginner-friendly CALM architecture-as-code examples to help you learn and practice using the Common Architecture Language Model (CALM).

---

## Use Case 1: API Gateway to Customer Service

- **Description:** Demonstrates how an API Gateway connects to a Customer Service using CALM JSON.
- **File:** `api-gateway-customer-service.json`


## Use Case 2: Microservice with Database

- **Description:** Demonstrates a microservice connected to its own database using CALM JSON.
- **File:** `microservice-database.json`

- **How to use:** Validate using CALM CLI:
```bash
calm validate -p <pattern>.json -a microservice-database.json

