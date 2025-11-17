# 🌟 Wrenix Mart

> Modern • Scalable • Secure E-Commerce Engineering

<p align="center"> <img src="https://raw.githubusercontent.com/github/explore/main/topics/ecommerce/ecommerce.png" width="120" /> </p> <p align="center"> <b>A complete e-commerce ecosystem powered by Next.js, Spring Boot, PostgreSQL, Redis, Docker & Kubernetes.</b> </p>
🏷️ Badges
<p align="center"> <!-- Tech Stack Badges --> <img src="https://img.shields.io/badge/Frontend-Next.js-black?logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Backend-Spring%20Boot-6DB33F?logo=springboot&logoColor=white" /> <img src="https://img.shields.io/badge/Database-PostgreSQL-316192?logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Cache-Redis-DC382D?logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/Container-Docker-2496ED?logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Orchestration-Kubernetes-326CE5?logo=kubernetes&logoColor=white" /> <br> <!-- Project Status Badges --> <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat" /> <img src="https://img.shields.io/badge/License-Private-red?style=flat" /> </p>

## What is Wrenix Mart?

Wrenix Mart is a modern e-commerce platform built with a scalable architecture, secure authentication, cloud-native deployment, and clean modular development practices.

This organization contains all repositories for the full product ecosystem, including:

- Customer-facing online storefront
- Product, order & inventory management
- End-to-end secure authentication
- High-performance backend
- Fully containerized deployment stack

## Technology Overview

### Frontend (Next.js)

- Next.js App Router
- TypeScript
- Tailwind CSS
- TanStack Query / Zustand
- Axios API layer
- Jest + React Testing Library

### Backend (Spring Boot)

- Java 17+
- Spring Boot microservice
- PostgreSQL
- Redis
- OAuth2 / JWT
- Kafka / Kafka (Queues)

### Infrastructure

- Docker & Docker Compose
- Kubernetes (K8s) with manifests
- GitHub Actions CI/CD
- NGINX ingress
- Cloud-ready deployment

## Repositories in This Organization

|Repository |	Description |
|ecommerce-frontend |	Next.js e-commerce front-end application |
|ecommerce-backend |	Spring Boot backend service with API, auth, DB, Redis |
|ecommerce-infra |	Infrastructure: Docker, Kubernetes, CI/CD pipelines |

## Branching Strategy

> main      → Production
> dev       → Integration / Staging
> feature/* → Feature development

### Pull Request Requirements

- 1 reviewer approval
- CI checks must pass
- Jest/Maven tests must pass
- No direct commits to main or dev

## Development Workflow

1. Create branch → feature/<task-name>
2. Commit changes & open PR → dev
3. CI runs automated build + tests
4. Reviewer approves
5. Merge into dev
6. Version bump + QA checks
7. Merge dev → main

## Documentation & Resources

| Area |	Location |
|Frontend Docs |	See ecommerce-frontend/README.md |
|Backend Docs |	See ecommerce-backend/README.md|
|Infra Docs |	See ecommerce-infra/README.md|
|API Specs |	Backend Wiki|
|Deployment |	Infra Wiki|

## Security

If you discover a vulnerability, report it privately to the admin team.
Do not disclose it publicly.

## 🤝 Contributing

We welcome contributions from internal developers!

- Follow branch & commit naming conventions
- Use templates for Issues & Pull Requests
- Respect code review requirements
- Maintain clean, secure, tested code

👋 Welcome to the Team!

Explore the repositories, read the docs, and start building.
We’re excited to have you as part of Wrenix Mart. 🚀
