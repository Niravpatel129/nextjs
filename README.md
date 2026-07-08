# Next.js API Example

A small legacy Next.js playground that demonstrates a React page calling a serverless API route. The app fetches `/api/date` from the browser and renders the date returned by the Node.js API handler.

## What this project shows

- Basic Next.js page routing with the `pages/` directory
- A simple client-side fetch from a React component
- A Node-backed API route under `pages/api`
- Inline `styled-jsx` styling
- Legacy ZEIT Now / early Vercel deployment structure

## Tech stack

- Next.js 9
- React 16
- Node.js API routes
- styled-jsx

## Getting started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open the app locally:

```text
http://localhost:3000
```

## Available scripts

```bash
npm run dev      # Start the Next.js dev server
npm run build    # Build the app for production
npm run start    # Start the production server
```

## Project structure

```text
pages/
  index.js        # Main page that fetches the API date
  api/            # Serverless API routes
static/           # Static assets for the legacy Next.js setup
```

## Status

This is an older learning/demo repository, not a production app. It is useful as a minimal reference for how Next.js pages and API routes work together.
