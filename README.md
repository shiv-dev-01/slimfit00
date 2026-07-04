# SlimFitRx Checkout

A React-based checkout portal for **SlimFitRx**, providing product selection, payment processing, coupon validation, and order confirmation.

## Features

- **Checkout flow** â€” Multi-step checkout with contact details, shipping, and payment
- **Coupon validation** â€” Promo code verification
- **Thank-you page** â€” Post-order confirmation (/thankyou-page)
- **Error handling** â€” Dedicated error page for invalid routes
- **State validation** â€” Shipping state eligibility checks
- **Sticky.io integration** â€” Payment SDK for order processing

## Tech Stack

| Technology | Purpose |
|---|---|
| React 18 | UI framework |
| Create React App | Build tooling & dev server |
| React Router v6 | Client-side routing |
| Tailwind CSS | Utility-first styling |
| Axios | HTTP client for API calls |

## Prerequisites

- **Node.js** 18 or later

## Getting Started

```bash
git clone https://github.com/shiv-dev-01/slimfit00.git
cd slimfit00
npm install
npm start
```

## Available Scripts

| Script | Description |
|---|---|
| `npm start` | Start development server |
| `npm run build` | Create production build in `build/` |
| `npm test` | Run test suite |

## API Configuration

| Setting | Value |
|---|---|
| **Base URL** | `https://panel.whitelabelmd.com/formscripts/api/` |
| **Coupon API** | `https://panel.whitelabelmd.com/formscripts/api/check_coupons` |

API endpoints are defined in `src/utils/Constant.js`.

## Production Build

```bash
npm run build
```

Deploy the contents of the `build/` directory to any static hosting provider.
