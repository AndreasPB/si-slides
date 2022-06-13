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
  - Decoupling of clients from services
  - Data transformation/conversion
  - Routing between services

---

# Code
<img src="static/message_struct.png">
<img src="static/esb_createmessage.png" height="350px">

---
# Code
<img src="static/esb_readmessages.png">

---

# Driver

Hoppscotch/Postman

- https://hoppscotch.io/

---

- Pros
  - Centralized integration makes for easier development of services
  - Many transport protocols can be supported at once
  - Keeps you from implementing all of your protocols in every service

---

- Cons
  - Single point of failure
  - ESB becomes a monolith and difficult to maintain

- Alternatives
  - Smart endpoints and dumb pipes

---

# Microservices

<img src="static/containers.png" height="400px">

---

# Hosted

- Vercel:
  - Frontend
    - https://si-mandatory1.vercel.app/

- Hetzner:
  - Backend
    - http://python.si.streamchaser.tv/docs
  - ESB
    - http://78.46.225.191:9999/


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
