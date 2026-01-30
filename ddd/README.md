---

# Introduction to Domain‑Driven Design (DDD)

Domain‑Driven Design is an approach to building software that places the business domain at the center of the system. 
Instead of letting frameworks, databases, or messaging technologies dictate the structure of the application, 
DDD organizes the code around the business rules, processes, and concepts that the system is meant to support.

The core idea is simple: the domain and its logic should remain stable even when the surrounding technology changes. 
Whether the system uses REST or messaging, SQS or Kafka, PostgreSQL or another database, the business logic should not be affected. 
This separation makes the system easier to maintain, test, and evolve.

To achieve this, DDD promotes a layered architecture where each layer has a clear responsibility and strict dependency direction. 
The outer layers adapt the application to external technologies, while the inner layers contain the business rules and remain independent of frameworks.

The following article describes these layers in detail and explains how responsibilities are divided between them. 
It outlines how API endpoints, core logic, and infrastructure components should be organized to keep the system clean, 
modular, and technology‑agnostic.

---
