# e-plantShopping

A React e-commerce application for browsing and purchasing plants, built with Redux for state management.

## Live Demo

[https://carlosarturoleon.github.io/e-plantShopping](https://carlosarturoleon.github.io/e-plantShopping)

## Features

- Browse plants organized by category (Air Purifying, Aromatic, Insect Repellent, Medicinal, Low Maintenance)
- Add plants to a shopping cart
- Cart icon displays live item count
- "Add to Cart" button disables once an item is added
- Adjust item quantity with + / - buttons
- Remove individual items from the cart
- View subtotal per item and total cart amount
- Continue shopping from the cart view

## Tech Stack

- [React](https://react.dev/) — UI library
- [Redux Toolkit](https://redux-toolkit.js.org/) — state management
- [React Redux](https://react-redux.js.org/) — React bindings for Redux
- [Vite](https://vitejs.dev/) — build tool
- [GitHub Pages](https://pages.github.com/) — deployment

## Project Structure

```
src/
├── main.jsx          # Entry point, wraps app in Redux Provider
├── App.jsx           # Root component
├── store.js          # Redux store configuration
├── CartSlice.jsx     # Redux slice: addItem, removeItem, updateQuantity
├── ProductList.jsx   # Plant catalog page
├── CartItem.jsx      # Shopping cart page
└── *.css             # Component styles
```

## Getting Started

### Install dependencies

```bash
npm install
```

### Run locally

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

### Deploy to GitHub Pages

```bash
npm run deploy
```
