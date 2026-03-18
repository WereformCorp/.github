# WeReform
**A modular digital ecosystem focused on building next-generation social and media platforms**

---

# 🚀 About

WeReform is an emerging technology organisation focused on building a **scalable digital ecosystem of platforms, services, and infrastructure**, with a primary emphasis on social media and content distribution.

Its flagship direction centers around **BEGENONE**, a video-based social platform designed to enable new forms of user interaction and content sharing. :contentReference[oaicite:0]{index=0}  

At a system level, WeReform is engineering:
- A modular frontend architecture (package-driven)
- A transition from monolithic systems to distributed services
- A foundation for scalable, media-heavy platforms

**Core problem being addressed:**
Modern platforms struggle with scalability, modularity, and long-term maintainability.  
WeReform is building systems designed to evolve structurally over time, not just feature-wise.

---

# 🧠 Architecture Overview

### System Direction
```

Legacy Monolith
↓
Modular Package Layer (Frontend-first)
↓
Service-Oriented / Distributed Architecture (target)

```

### Current Architecture Layers

**1. Application Layer**
- Video platform (BEGENONE)
- Channel systems
- Feed systems (short-form + text-based)

**2. Modular Package Layer**
- Independent UI and logic packages
- Designed for reuse across applications
- Enables faster feature iteration

**3. Backend Layer (Legacy)**
- Centralized Node.js backend
- Handles authentication, media, and business logic

**4. Infrastructure (Implied / Partial)**
- Cloud-based storage and delivery
- Media processing pipelines
- Architecture defined through system diagrams

---

# 📦 Repositories

## Core Services

### BEGENONE-monolith-legacy
- Original full-stack backend powering the platform
- Handles authentication, media workflows, and core logic  
- **Tech:** Node.js, MongoDB, AWS (S3), Stripe  
- **Status:** Legacy foundation (archived, replaced directionally)

---

## Frontend Applications (Modular System)

### begenone-pkgm-api
- Core API interaction layer for authenticated requests  
- **Tech:** JavaScript (API abstraction layer)

### begenone-pkgm-channel
- Channel page system (creator profiles, layouts, navigation)  
- **Tech:** React Native / Expo

### begenone-pkgm-settings
- User configuration and preference management UI  
- **Tech:** React Native

### begenone-pkgm-video
- Video components (player, feed rendering, metadata UI)  
- **Tech:** React Native

### begenone-pkgm-wire
- Lightweight text-first content system (“Wires”)  
- **Tech:** React Native

---

## Shared Packages / Libraries

### begenone-pkgm-shared
- Core design system and reusable UI primitives  
- Used across all modules for consistency  
- **Tech:** React Native

---

## Infrastructure / DevOps

### architectural-diagrams
- System architecture blueprints and flow diagrams  
- Includes:
  - Authentication flows
  - Media pipelines
  - Service relationships  
- **Tech:** Mermaid diagrams

---

# ⚙️ Tech Stack

### Languages
- JavaScript (primary)
- TypeScript (partial / implied)

### Frameworks
- Node.js
- React Native / Expo

### Cloud & Infrastructure
- AWS S3 (media storage)
- MongoDB Atlas (database)
- Stripe (payments)

### Tooling
- Modular package architecture (NPM ecosystem)
- Mermaid (system design visualization)

---

# 🎯 Vision

Based on internal systems and external positioning:

WeReform is building toward:
- A **multi-platform digital ecosystem**
- A **video-first social platform (BEGENONE)**
- A **modular architecture enabling scalable product expansion**

Externally, it positions itself as a **provider of multiple products and services under a broader ecosystem vision**.

---

# 📈 Status

### Current State
- Functional legacy platform architecture exists
- Modular frontend ecosystem actively structured
- System design and decomposition underway

### In Progress
- Migration from monolith to modular system
- Expansion of reusable packages
- Refinement of architecture boundaries

### Not Yet Evident Publicly
- Fully deployed distributed backend services
- Production-grade DevOps pipelines (CI/CD, observability)
- Public-facing unified platform application

### Maturity Assessment
**Early-stage platform architecture with active structural transition**

---

# 🤝 Contributing

Contribution guidelines are not formally defined yet.

The repository structure suggests a controlled and evolving architecture where contributions would require alignment with:
- Modular package standards
- System-wide consistency
- Architecture direction

---

# 📬 Contact / Links

- GitHub: https://github.com/WereformCorp  
- Website: https://wereform.co  
- LinkedIn: https://au.linkedin.com/company/world-ecosystem-reform  

---

# ⚠️ Positioning Summary

WeReform is best defined as:

> A modular engineering ecosystem building a scalable, video-first social platform and its underlying infrastructure.

It is not a finished platform.  
It is a system actively being structured into one.
