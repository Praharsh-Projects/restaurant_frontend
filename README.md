# restaurant_frontend

Frontend web app for a restaurant ordering platform built with React.

## What This Project Is
- Customer-facing and restaurant-facing UI for browsing restaurants/products and placing orders.
- Integrates with a backend API (configured via `proxy` / direct API URLs in components).
- Includes authentication, profile, cart, and order screens.

## Main Features
- User authentication flow (signup/login + Google OAuth package support).
- Dashboard with restaurant and product discovery.
- Restaurant detail and product detail pages.
- Cart and pre-order/checkout related flows.
- User profile with personal info and address management.
- Restaurant portal pages (auth, dashboard, product management).

## Routes Included
Examples from `src/App.js`:
- `/`
- `/dashboard`
- `/allRestaurants`
- `/restaurant/:id`
- `/allProducts`
- `/product/:id`
- `/cart`
- `/orders`
- `/restaurants/*`

## Tech Stack
- React (Create React App)
- React Router
- Axios
- Redux Toolkit / React Redux
- Bootstrap + custom CSS

## Run Locally
```bash
npm install
npm start
```

App runs on `http://localhost:3000` by default.

## Notes
- `package.json` proxy points to `http://localhost:5000`.
- Some components also call a deployed backend URL directly.
