# System Integration

---

# Architecture

<img src="static/architecture.png" height="400px">

---

# Concept

<img src="static/esb_concept.png" height="400px">

---

# Demo

---

# ESB

- Motivation
  - Decoupling of clients from services
  - Data transformation/Conversion between transport protocols
  - Routing between services

---

# Code
<img src="static/message_struct.png">
<img src="static/esb_createmessage.png" height="350px">

---
# Code
<img src="static/esb_readmessages.png">

---

- Pros
  - Centralized integration logic makes for easier development of services
  - Many transport protocols can be supported at once
- Cons
  - Single point of failure
  - ESB becomes a monolith, more difficult to maintain
- Alternatives
  - Smart endpoints and dumb pipes

---

# Microservices

Containerization
  
<img src="static/containers.png">

---

- Database per Service
- Deployment
  - Serverless frontend with Vercel
- API Gateway

---

# Security

- Access Token
  - JWT

<img src="static/login.png">

---

Dependency Injection

<img src="static/verify_mitid.png">

<img src="static/dependency_injection.png">

---

# 

---
