# Node.js Backend Learning — From Core Runtime to REST API

This repository documents my **structured Node.js learning path**, starting from **Node.js core internals** to **real-world REST API implementation with database and authentication**.

The focus is **understanding how Node.js works**, then **using it correctly to build backend systems**, not jumping straight to frameworks without foundations.

---

## Learning Scope

This learning is based on **two stages**:

1. **Node.js Core & Runtime (Foundation)**
   - https://youtu.be/b39Xqf5iyjo?si=DD2oQbr-j9MGMgwr
2. **Backend API Development (Applied Practice)**
   - https://youtu.be/6v8JXecArqE?si=UUkwj_0qXROLmWyN

Both stages are mandatory. No shortcuts.

---

## Stage 1 — Node.js Core (Inprogress)

### Runtime & Architecture
- Concurrency vs parallelism
- Thread pool model
- Blocking vs non-blocking I/O
- Node.js architecture (V8, libuv)
- Worker Threads
- Cluster

Understanding **why Node behaves the way it does**, not just how to write code.

---

### Core Standard Library
- `os`
- `path`
- `fs`
- `dns`
- `events`
- `globals`
- `process`
- `buffer`
- `stream`
- `timer`
- `net`
- `url`
- `util`
- `zlib`
- `console`
- `readline`

Focus:
- Async vs sync behavior
- Streams vs buffers
- Low-level networking and I/O

---

### Module System
- CommonJS modules
- `require` mechanism
- Module scope & global async behavior

---

### HTTP (Without Framework)
- HTTP client
- HTTP server
- Request / response lifecycle

No Express abstraction at this stage.

---

## Stage 2 — Backend API Development ()

### Requirement Analysis
- User management
- Contact management
- Address management
- Entity separation and relationship modeling

Design first. Code second.

---

### API Specification
- User API spec
- Contact API spec
- Address API spec
- RESTful endpoint structure
- CRUD + search APIs

Clear contract before implementation.

---

### Database Integration
- Database setup
- User, Contact, Address models
- Relational data handling

Focus:
- Data modeling
- API-to-database mapping

---

### Authentication
- User registration
- Login
- Logout
- Get user
- Update user

Covers basic authentication flow required in real backend systems.

---

### CRUD API Implementation
- Create / Read / Update / Delete
- Nested resources
- Search and listing endpoints

This is **actual backend work**, not demo code.

---

### Manual API Testing
- Endpoint testing without automation
- Request validation via manual inspection

Enough for foundational learning.

---

## Current Status

- 🟢 Node.js Core & Runtime — Completed  
- 🟢 REST API with Database & Auth — Completed  
- 🟡 Production Hardening — Pending  

---

## What Is NOT Covered Yet

Intentionally excluded from these stages:

- Automated testing (unit & integration)
- Centralized error handling strategy
- Input validation library (Zod / Joi)
- Environment & configuration management
- Security hardening
- Production deployment practices

These belong to the **next phase**, not beginner foundations.

---

## Learning Philosophy

- Node.js is a **runtime**, not a framework
- Express is an **abstraction**, not knowledge
- Backend engineering starts with **system understanding**
- Frameworks are tools, not skills

This repository exists to prove **backend fundamentals**, not to showcase UI or libraries.

---

## Next Phase (Planned)

- Validation & error architecture
- Express structure (controller / service / repository)
- Automated testing
- Security basics
- Production readiness

Only after this phase does enterprise backend discussion make sense.
