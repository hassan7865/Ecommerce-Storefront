# Ecommerce-Storefront

React storefront for a sample ecommerce shop. Talks to [Ecommerce-API](https://github.com/hassan7865/Ecommerce-API).

## Overview

Create React App client with product browsing, cart, auth, and order detail pages. State is managed with Redux Toolkit and redux-persist; UI uses MUI and styled-components.

## Stack

- React 18 (Create React App)
- React Router 6
- Redux Toolkit + redux-persist
- MUI, Emotion, styled-components
- Axios
- SweetAlert2, Lottie helpers, easyinvoice

## Structure

```
src/
  Pages/          # Home, ProductList, SingleProduct, Cart, Login, Register, Order
  Components/     # Navbar, slider, categories, products, Redux slices, API helpers
  App.jsx
public/
```

## Getting started

```bash
npm install
# or: yarn
npm start
```

Build:

```bash
npm run build
```

API base URL is set in `src/Components/url.js` (defaults to the Vercel API). Point it at your own API for local work.

## Features

- Browse products by category and open product detail
- Register / login (JWT stored via persisted Redux state)
- Cart and order detail for authenticated users
