# Project Marketplace — Backend Foundation

This package adds a real local API and database to the existing HTML MVP.

## Run locally
1. Install Node.js 20+.
2. Open this folder in a terminal.
3. Run `npm install`.
4. Run `npm start`.
5. Open `http://localhost:3000`.

The API is under `/api` and creates `marketplace.db` automatically.

## Current endpoints
- `GET /api/health`
- `GET /api/categories`
- `GET /api/providers?q=&category=&city=`
- `GET /api/providers/:id`
- `POST /api/requests`
- `GET /api/requests/:id/quotes`
- `POST /api/quotes`
- `POST /api/bookings`

## Important
This is a development foundation, not a production payment/authentication system. Before public launch, add secure authentication, password hashing, email/phone verification, authorization checks, PostgreSQL, backups, file storage, payment-provider webhooks, audit logs, rate limiting, monitoring and legal/compliance controls.
