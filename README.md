# e-plantShopping

**e-plantShopping** is a React-based e-commerce shopping cart application for browsing and purchasing houseplants. It was built as part of a peer-graded assignment using React, Redux Toolkit, and Vite.

## Overview

The e-plantShopping application lets users explore a catalog of plants organized by category, add items to a shopping cart, and manage their selections before checkout. State across the app is handled with Redux Toolkit so the cart stays in sync as users navigate.

### Features

- **Landing page** — an inviting entry point that introduces the shop and links into the product catalog.
- **Product listing** — plants grouped by category (e.g. aromatic, medicinal, air-purifying) with images, descriptions, and prices.
- **Shopping cart** — add plants to the cart, increase or decrease quantities, remove items, and view a running total.
- **Cart badge** — a live item count in the header that updates as the cart changes.

## Tech Stack

- **React 18** — UI components
- **Redux Toolkit** & **React Redux** — global cart state management
- **Vite** — development server and build tooling

## Getting Started

Install dependencies and start the development server:

```bash
npm install
npm run dev
```

### Available Scripts

- `npm run dev` — start the local development server
- `npm run build` — build the app for production
- `npm run preview` — preview the production build locally
- `npm run lint` — run ESLint over the project
- `npm run deploy` — deploy the built app to GitHub Pages

## Deployment

The e-plantShopping app is deployed to GitHub Pages at:
https://hugocasildo.github.io/e-plantShopping
