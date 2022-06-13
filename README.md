# System Integration

---

# Architecture

<img src="static/architecture.png" height="400px">

---

# Concept

<img src="static/esb_concept.png" height="400px">

---

<video controls>
  <source src="static/si-demo.mp4" type="video/mp4">
</video>

---

# ESB

- Motivation
  - Simplifies the interfacing of services
  - Data transformation/conversion
  - Routing between services

---

<img src="static/message_struct.png">
<img src="static/esb_createmessage.png" height="350px">

---

<img src="static/esb_readmessages.png">

---

# Driver

Hoppscotch/Postman

- https://hoppscotch.io/

---

- Cons
  - Single point of failure
  - ESB can become a monolith and difficult to maintain

---

# Containers

Database per service

<img src="static/containers.png" height="400px">

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

# Deployment

- Multiple service instances per host
- Single Service Instance per host
- Serverless deployment

---

## Multiple 

- Pros
  - Efficient resource utilization

- Cons
  - Conflicting resource requirements

---

## Single

- Pros
  - Clear isolation
  - No conflicts in resources or dependencies

- Cons
  - Resource utilization overhead
  - Complexity in scaling

---

## Serverless

- Pros
  - Elastic scaling
  - Reduced time spend on low-level infrastructure
  - Out-of-the-box reverse proxy

- Cons
  - Limitations/constraints

---

# Our hosting

- Vercel:
  - Frontend
    - https://si-mandatory1.vercel.app/

- Hetzner:
  - Backend
    - http://python.si.streamchaser.tv/docs
  - ESB
    - http://78.46.225.191:9999/

---
