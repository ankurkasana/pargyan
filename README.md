# Pargyan Bookstore (React)

A responsive bookstore storefront plus a seller dashboard demo built with React, Vite and Lucide icons.

## Requirements
- Node.js 18+ (recommended)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite (usually http://localhost:5173).

## Build for production
```bash
npm run build
npm run preview
```

## Included features
- Responsive home page, categories and book listing
- Search, category filter and price/name sorting
- Add to cart, quantity changes and wishlist
- Demo login/register modal
- Checkout demo and order history
- Seller dashboard: add/edit/delete books, inventory overview and order status updates
- Browser localStorage persistence

## Important demo limitations
This is a front-end React starter. Login is a demo (not secure authentication), orders are stored in the current browser, and checkout does not charge a payment method. Product cover images use remote image URLs. For a real public marketplace, connect a backend (Node.js/Express), database (MongoDB or PostgreSQL), secure authentication, image storage, payment gateway and shipping provider. Do not use the demo login or localStorage as production security.
