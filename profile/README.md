# api-craft Ecosystem

Welcome to **api-craft** — a comprehensive, modular API ecosystem designed to simplify authentication, caching, payments, and more for modern web applications.

---

## Overview

**api-craft** is a modular set of APIs and services built to provide seamless integration of essential backend features such as:

- OAuth 2.0 based authentication and authorization (`/oauth`)
- High-performance caching layer
- Flexible payment processing system
- Additional utilities and services to build robust backend applications

Each module is designed to work independently or as part of the larger **api-craft** ecosystem, allowing you to pick and choose components based on your project needs.

---

## Modules

### 1. OAuth Module (`/oauth`)

- Implements OAuth 2.0 protocol for secure authorization.
- Supports multiple grant types: Authorization Code, Client Credentials, Refresh Tokens, and more.
- Provides token issuance, revocation, and introspection endpoints.
- Easy integration with external identity providers or as a standalone auth server.
- Hooks and middleware to protect your API routes effortlessly.

### 2. Cache Module

- Fast, in-memory caching for API responses, sessions, and data.
- Supports multiple cache stores (Redis, Memcached, or in-memory).
- Configurable cache expiration and invalidation strategies.
- Integrates with other **api-craft** modules to optimize performance.

### 3. Payments Module

- Unified payments API supporting multiple gateways (Stripe, PayPal, etc.).
- Handles payment intents, subscriptions, refunds, and webhooks.
- Secure payment data processing and PCI compliance considerations.
- Built-in retry logic and error handling for robust payment flows.

---

## Installation

You can install each module independently via npm/yarn or clone the entire ecosystem repository.

```bash
# Example: installing OAuth module
npm install @api-craft/oauth

# Example: installing Cache module
npm install @api-craft/cache

# Example: installing Payments module
npm install @api-craft/payments
```
