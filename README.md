# JPMorgan Midas Core Simulation

Spring Boot microservice that processes financial transactions using Kafka and exposes REST APIs for querying user balances.

## Features

- Kafka transaction listener
- External Incentive API integration
- Transaction database storage
- Balance update logic
- REST API endpoint `/balance`

## Tech Stack

- Java
- Spring Boot
- Kafka
- Maven
- REST APIs

## API Endpoint

GET /balance?userId={id}

Returns:

{
  "amount": 100.0
}
