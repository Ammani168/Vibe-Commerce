🚀 Vibe Commerce – Mock E-Commerce Cart (Full Stack Assignment)

A fully functional full-stack shopping cart app built for Vibe Commerce screening.
Implements basic e-commerce flows: product listing, add/remove cart items, totals, and mock checkout (no real payments).

🧩 Technologies Used

🛠️Frontend
  * React
  * Vite
  * CSS / Tailwind / Vanilla (your choice)
  * Fetch API
🛠️Backend
  * Node.js
  * Express
  * SQLite3
  * UUID

📌 Features
Frontend (React)

- Product grid with Add to Cart button

- Cart page with:

 - Show items, quantity, price

 - Update or remove items

 - Auto calculates total

- Checkout modal with:

  - Name & email form

  - Fake receipt output

- Fully responsive UI

📌Backend (Node + Express + SQLite)
  
* REST API endpoints:

GET    /api/products
GET    /api/cart
POST   /api/cart
DELETE /api/cart/:id
POST   /api/checkout

- Uses SQLite DB for persistence

- Auto-seeds 7 sample products

- Cart stored in DB

- Implemented

- DB persistence

- UUID-based cart items

- Clean folder structure

- Simple error handling

📁 Project Structure
vibe-commerce/
 ├── backend/
 │    ├── server.js
 │    ├── db.sqlite
 │    └── package.json
 ├── frontend/
 │    ├── src/
 │    └── package.json
 ├── README.md

🛠️ Installation & Setup
1️⃣ Clone the repo
git clone https://github.com/Ammani168/Vibe Commerce

⚙️ Backend Setup (Node + Express + SQLite)
Install dependencies
cd backend
npm install

Start backend server
npm start

Server runs at:
👉 http://localhost:4000

Database automatically seeds 7 products.

💻 Frontend Setup (React + Vite)
Install dependencies
cd ../frontend
npm install

Start React app
npm start
# or
npm run dev

Frontend runs at:
👉 http://localhost:5173
