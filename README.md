# APIForge — Instant REST API from Database Schema

Stop writing boilerplate CRUD code. APIForge reads your database schema and generates a production-ready REST API in seconds.

## Why APIForge?

Building REST APIs is repetitive, error-prone, and takes hours of boilerplate code. Existing tools are either too complex (PostgREST), too expensive (Supabase), or require you to migrate your entire stack. APIForge works with your **existing database** — no migration required.

## Features

- **Zero Config** — Point it at your database, get an API
- **Multi-Database** — PostgreSQL, MySQL, SQLite
- **Auth Built-In** — JWT authentication out of the box
- **Typed SDKs** — Auto-generated TypeScript & Python SDKs
- **OpenAPI Docs** — Interactive Swagger UI included
- **Pagination & Filtering** — Smart defaults, customizable
- **CLI + GitHub Action** — Run locally or in CI/CD

## Quick Start

```bash
# Install
npm i -g apiforge

# Generate API from existing database
apiforge generate --db postgres://user:pass@localhost/mydb --output ./api

# Start the server
cd api && npm start
```

Your REST API is now running at `http://localhost:3000` with full CRUD endpoints, auth, and docs.

## Pricing

| Plan | Price | Features |
|------|-------|----------|
| Free | $0 | 1 table, basic CRUD |
| Pro | $29/mo | Unlimited tables, auth, SDKs, OpenAPI |
| Team | $79/mo | Unlimited projects, priority support, CI/CD |

## Comparison

| Feature | APIForge | PostgREST | Supabase | Hasura |
|---------|----------|-----------|----------|--------|
| Zero-config | ✅ | ❌ | ❌ | ❌ |
| Works with existing DB | ✅ | ✅ | ❌ | ✅ |
| Auth built-in | ✅ | ❌ | ✅ | ❌ |
| Typed SDKs | ✅ | ❌ | ✅ | ❌ |
| Free tier | ✅ | ✅ | ✅ | ❌ |
| Self-hosted | ✅ | ✅ | ❌ | ✅ |
| OpenAPI docs | ✅ | ✅ | ❌ | ❌ |
