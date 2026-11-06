# Nguyễn Văn Tứ Vinh

**Full-Stack Developer · TypeScript · React · Next.js · NestJS**

I build web applications with a focus on **maintainable architecture, dependable APIs, data integrity, and practical AI integration**. My public repositories document not just features, but also engineering decisions, testing strategies, and project limitations.

**Current interests:** full-stack product development · backend architecture · AI-assisted search · developer experience

---

## Selected projects

### 01 · [ShopMind — AI-powered product discovery](https://github.com/luciusvie2712/shopmind)

An AI-assisted shopping application that translates natural-language requests into structured intent, applies deterministic product constraints, and combines keyword and vector retrieval.

- **Stack:** Next.js, NestJS, TypeScript, PostgreSQL, pgvector, Redis, BullMQ, Gemini.
- **Architecture:** Modular backend with separate API and worker processes; PostgreSQL remains the source of truth for product facts.
- **Engineering practices:** CI workflows, documented testing (Jest/Supertest and Playwright), background jobs, rate limiting, and explicit architecture trade-offs.
- **Status:** Documented MVP. Production infrastructure and external provider configuration are not fully completed.

[Source & setup](https://github.com/luciusvie2712/shopmind) · [Architecture](https://github.com/luciusvie2712/shopmind#architecture) · [Testing](https://github.com/luciusvie2712/shopmind#testing)

### 02 · [FLUIVIX — Multilingual fashion storefront](https://github.com/luciusvie2712/Fashion-E-commerce-Website)

A responsive e-commerce frontend covering catalog discovery, product variants, cart and checkout journeys, and order-management screens.

- **Stack:** React, TypeScript, Vite, Zustand, Tailwind CSS, React Hook Form, Zod, i18next.
- **Engineering focus:** Reusable components, typed state, form validation, localization, responsive design, and E2E test infrastructure.
- **Scope:** 34 documented route patterns and five interface languages.
- **Status:** Frontend demonstration with sample data; authentication, payments, orders, and fulfillment are simulated.

[Source & documentation](https://github.com/luciusvie2712/Fashion-E-commerce-Website)

### 03 · [Spotify Basic Clone — Music management application](https://github.com/luciusvie2712/spotify-basic-clone)

A full-stack learning project with separate listener, administration, and REST API applications.

- **Stack:** React, Vite, Express, MongoDB, Mongoose, Cloudinary.
- **Engineering focus:** REST endpoints, media uploads, data modeling, and client–server integration.
- **Status:** Educational prototype, not a production streaming platform. The media-management API currently needs authentication and additional security hardening before public deployment.

[Source & local setup](https://github.com/luciusvie2712/spotify-basic-clone)

---

## Engineering toolkit

| Domain | Technologies and practices |
| --- | --- |
| **Frontend** | TypeScript, JavaScript, React, Next.js, Vite, Tailwind CSS, Zustand |
| **Backend** | Node.js, NestJS, Express, REST APIs, modular application architecture |
| **Data & infrastructure** | PostgreSQL, pgvector, MongoDB, Redis, Docker, BullMQ |
| **Quality & delivery** | GitHub Actions, CI/CD, Jest, Supertest, Playwright |
| **Applied AI** | Gemini integrations, structured LLM outputs, hybrid retrieval, grounded responses |

## How I approach software engineering

- **Keep boundaries explicit.** Separate UI, business logic, persistence, and external providers where the project requires it.
- **Protect data integrity.** Treat application databases and validated inputs—not generated text—as authoritative.
- **Make systems understandable.** Document architecture, setup, design trade-offs, limitations, and reproducible development steps.
- **Build with verification in mind.** Use automated checks where available and distinguish implemented functionality from planned work.

## Additional work

- [Chat App](https://github.com/luciusvie2712/chat-app-base) — React/TypeScript and Express/MongoDB messaging prototype.
- [Konect](https://github.com/luciusvie2712/social-media-konect-fe) — React-based social application frontend prototype.

---

**Interested in my engineering work?** Start with [ShopMind](https://github.com/luciusvie2712/shopmind) for backend and AI integration, or [FLUIVIX](https://github.com/luciusvie2712/Fashion-E-commerce-Website) for frontend architecture and user experience.

[View all repositories](https://github.com/luciusvie2712?tab=repositories)
