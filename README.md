# Stockify — Inventory Management Web App (Version 1)

[View Stockify V2](https://github.com/prxtxks/stockify-v2)

![Stockify Mini UI Mocks](./Stockify/mocks.svg)

## Project Overview

**Stockify (V1)** is a clean and efficient inventory management web application designed for businesses that need a simple way to track products, manage stock levels, and process orders.

This version focuses on the **core system** only — no AI, no analytics — just a smooth and functional management workflow.

## Key Features

### Inventory Management
- Add, edit, and delete products  
- Track stock levels in real time  
- Categorize products for better organization  
- Basic low-stock alerts (rule-based)

### Order Management
- Create purchase orders  
- Track order progress (Pending → Shipped → Delivered)  
- Manage supplier details  
- View order history  

### User Management
- Role-based access: Admin & Staff  
- Secure login and authentication  
- Activity logs for transparency  

### Dashboard Overview
- Total products, orders, and users  
- Quick summaries and status indicators  
- Clean and minimal UI

## UI Mockups

> **Dashboard**

![Dashboard](./Stockify/dashboard.svg)

> **Orders Management**

![Orders](./Stockify/orders.svg)

> **Users & Access Control**

![Users](./Stockify/users.svg)

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (Flask) or Node.js  
- **Database:** MySQL / PostgreSQL  
- **Charts & Visuals:** Chart.js / basic JS visual components  

## System Workflow

1. **User Login** → Authenticated access based on roles  
2. **Dashboard** → High-level metrics and quick stats  
3. **Inventory Module** → Manage product data and stock  
4. **Orders Module** → Track incoming/outgoing orders  
5. **User Module** → Create & manage accounts  
6. **Reports (Basic)** → View inventory and order summaries  

## How to Run Locally

```bash
# Clone Repository
git clone https://github.com/yourusername/stockify-v1.git
cd stockify-v1

# Install Dependencies
pip install -r requirements.txt   # Flask version
# or
npm install                       # Node.js version

# Start Application
python app.py     # Flask
# or
npm start         # Node.js
```
