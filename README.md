# Architecture Portfolio – Java Architect

This repository presents my **architecture portfolio**, highlighting hands-on design experience in building **scalable, resilient, and maintainable Java-based distributed systems** using modern architectural patterns and cloud-native practices.

---

## 👤 About Me

**Shivendra Goel**  
Java Architect with 12+ years of experience designing and delivering enterprise-grade systems.  
Strong focus on **Clean Architecture**, **event-driven microservices**, **system reliability**, and **operational excellence**.

---

## 🎯 Architecture Focus Areas

- Microservices Architecture  
- Clean / Hexagonal Architecture  
- Event-Driven Systems  
- Domain-Centric Design  
- Reliability & MTTR Reduction  
- Cloud-Native Deployments  

---

## 🧩 Architecture Principles

- Business logic independent of frameworks and infrastructure  
- Clear service boundaries and ownership  
- Loose coupling through asynchronous communication  
- Design for failure and fast recovery  
- Backward-compatible evolution of systems  
- Container-first, cloud-native approach  

---

## 🏗 Architecture Showcase

### 1️⃣ Event-Driven Microservice on Kubernetes
🔗 Repository: https://github.com/Goel-S/event-driven-microservice-k8s-poc

**Objective**  
Design a cloud-native microservice supporting asynchronous communication, independent deployments, and operational resilience.

**Architecture Overview**
- Java & Spring Boot based microservice  
- Clean / Hexagonal Architecture (Ports & Adapters)  
- Apache Kafka for event-driven communication  
- REST APIs for synchronous interactions  
- Dockerized deployment on Kubernetes  

**Key Architectural Decisions**
- Adopted Clean Architecture to isolate domain logic  
- Used Kafka to decouple services and avoid synchronous dependencies  
- Designed stateless services for horizontal scalability  
- Enabled self-healing using readiness and liveness probes  

**Non-Functional Considerations**
- Scalability through Kafka and Kubernetes replicas  
- High availability using multi-pod deployments  
- Fault isolation using asynchronous messaging  
- Observability via logging and health endpoints  
- Rollback-first deployment strategy to reduce MTTR  

---

### 2️⃣ Product Service – Clean Architecture
🔗 Repository: https://github.com/Goel-S/product-service-clean-architecture-poc

**Objective**  
Demonstrate a production-style Java microservice with strong architectural boundaries and long-term maintainability.

**Architecture Overview**
- Domain layer containing core business rules  
- Application layer implementing use cases  
- Adapter layer handling REST and persistence concerns  

**Key Architectural Decisions**
- Applied Ports & Adapters for dependency inversion  
- Designed use-case driven application flow  
- Treated persistence as an infrastructure detail  

**Outcomes**
- High testability and maintainability  
- Easy evolution and technology replacement  
- Reduced regression risk during change  

---

## 🔄 Reliability & Operability

- Health checks and readiness/liveness probes  
- Automated rollbacks for failed deployments  
- Event-driven isolation to limit blast radius  
- Backward-compatible deployment strategy  

---

## 🧠 Architecture Ownership

- Defined service boundaries and integration patterns  
- Made architectural trade-offs aligned with business goals  
- Ensured architectural consistency across services  
- Guided teams on Clean Architecture and event-driven design  

---
