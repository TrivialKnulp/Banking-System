 # Banking System Project. Managed via Azure DevOps

## Overview
A cloud-native banking platform designed for high-availability transaction processing. This project demonstrates the implementation of microservices architecture with a focus on ACID consistency and distributed systems.

## Planned Microservices Architecture
To ensure scalability, the system will be decomposed into the following services:
- **Identity Service:** User authentication and KYC.
- **Account Service:** Managing multi-currency balances.
- **Transaction Engine:** Handling atomic transfers between ledgers.
- **Exchange Service:** Real-time currency conversion.

## Technology Stack
- **Languages:** .NET 8 (C#)
- **Database:** PostgreSQL (Transactional storage)
- **In-memory:** Redis (Caching balances)
- **Containerization:** Docker & Kubernetes
- **Orchestration:** Helm
- **CI/CD:** Azure Pipelines
