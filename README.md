# OtakuAtelier
OtakuAtelier is a creative studio where anime culture, technology, and craftsmanship come together to build immersive digital experiences.

## 🏷️ Tagline
Where Passion Becomes Design.

<p align="center">
  <img src="https://img.shields.io/badge/Stack-MERN-61DAFB?style=flat-square" />
  <img src="https://img.shields.io/badge/TypeScript-Strict-blue?style=flat-square&logo=typescript" />
  <img src="https://img.shields.io/badge/Framework-NestJS-E0234E?style=flat-square&logo=nestjs" />
  <img src="https://img.shields.io/badge/TailwindCSS-UI-38B2AC?style=flat-square&logo=tailwindcss" />
  <img src="https://img.shields.io/badge/Auth-JWT%20%7C%20OAuth2-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/API-GraphQL-purple?style=flat-square&logo=graphql" />
  <img src="https://img.shields.io/badge/Architecture-Microservices-black?style=flat-square" />
  <img src="https://img.shields.io/badge/Security-RBAC-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Messaging-Kafka-yellow?style=flat-square&logo=apachekafka" />
</p>


**Architecture:** Event-Driven,GraphQL  

## 🧠 Tech Stack Highlights

- Postgresql - IAM service
  
- MongoDB – Product catalogs, user data, orders, and event storage

- Node.js – Core runtime for backend services

- NestJS – Primary backend framework for scalable, modular services

- Express.js – Underlying HTTP platform and lightweight edge services

- GraphQL – Unified API gateway for client-facing queries and mutations

- TypeScript – End-to-end type safety across frontend and backend

- React – Storefront, admin, and internal dashboards

- Tailwind CSS – Utility-first, design-system-friendly UI styling

- FastAPI + PyTorch – Recommendation, search ranking, and personalization engines

---
## 🧩 Key Features
### 🛂 [Identity, Access & Multi-Tenancy](https://github.com/diptu/otakuatelier-iam-service)

- Unified identity system with RBAC / ABAC support

- Multi-tenant architecture for brands, studios, and creators

- Secure authentication using JWT, refresh tokens, and session rotation

- Organization, team, and role management out of the box

### 🛍️ Product & Catalog Management

- Flexible product models (physical, digital, limited editions, NFTs)

- Category, tag, and attribute-based catalog structure

- Variant, inventory, and pricing rule support

- Event-driven catalog updates for real-time consistency

### 🧾 Order, Checkout & Payments

- High-performance, idempotent checkout flow

- Distributed order lifecycle management (pending → fulfilled → refunded)

- Multi-payment gateway support (Stripe, local wallets)

- Fraud detection hooks and payment event auditing

### 🚚 Inventory, Shipping & Fulfillment

- Real-time inventory tracking with reservation logic

- Multi-warehouse and drop-shipping support

- Shipping rate calculation and fulfillment provider integrations

- Automated stock reconciliation via events

🤖 Personalization & Recommendations

- AI-powered product recommendations using FastAPI + PyTorch

- User behavior tracking via event streams

- Personalized homepages, collections, and search results

- Cold-start and popularity-based fallback strategies

### 🔍 Search, Discovery & Ranking

- Full-text and semantic search support

- Category-aware and intent-based ranking

- Boosting rules for promotions, trends, and exclusives

- Near real-time index updates via event streams

### 📊 Admin, Analytics & Observability

- Role-based admin and internal dashboards

- Real-time sales, conversion, and funnel analytics

- Distributed tracing, structured logging, and metrics

- Audit logs for security and compliance

### 🔁 Event-Driven & Scalable by Design

- Asynchronous communication using domain events

- Loose coupling between services for independent scaling

- Event replay and backfill support

- Designed to scale from 0 → 1M+ users

### 🎨 Frontend Experience

- Modern, responsive storefront built with React + Tailwind CSS

- Optimized for performance, accessibility, and SEO

- Themeable UI for brand and creator customization

- Smooth, app-like UX with GraphQL-powered data fetching

### 🔐 Security, Compliance & Reliability

- Secure-by-default service boundaries

- Rate limiting, abuse protection, and anomaly detection

- Data isolation per tenant

- GDPR-ready data handling and user consent management

### 🌍 Platform Extensibility

- Plugin-friendly architecture for custom features

- Webhook and API-first integrations

- Versioned GraphQL schema for backward compatibility

- Ready for marketplace and ecosystem expansion
