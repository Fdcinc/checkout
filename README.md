# Checkout Example with PayPal on Vercel

This project shows a minimal PayPal checkout flow implemented as Vercel serverless functions.

## Setup

1. Install dependencies (locally):

```bash
npm install
```

2. Set the PayPal credentials in your environment before running locally or deploying:

```bash
export PAYPAL_CLIENT_ID=your-client-id
export PAYPAL_CLIENT_SECRET=your-client-secret
```

3. Start the development server:

```bash
npm start
```

## API Endpoints

- `POST /api/create-order` – creates a new PayPal order and returns its ID.
- `POST /api/capture-order` – captures a created order.

These endpoints are ready to deploy on Vercel as serverless functions.
