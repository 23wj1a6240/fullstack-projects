# Leafy: simple e-commerce store

Express.js + SQLite backend, vanilla HTML/CSS/JS frontend.

## Run
    npm install
    npm start        # http://localhost:3000

Set `JWT_SECRET` in production. The database (`shop.db`) is created and seeded on first run.

## Features
- Product listing with search and category filter
- Product detail page
- Cart (stored in the browser, quantities limited by stock)
- Registration and login (bcrypt hashes, JWT)
- Order processing: the server recalculates prices, checks stock and writes the order in one transaction
- Order history per user

## API
POST /api/register, POST /api/login, GET /api/products, GET /api/products/:id, POST /api/orders, GET /api/orders
