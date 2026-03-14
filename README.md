# 📦 CoreInventory – Inventory Management System

## 🚀 Odoo Hackathon Project

CoreInventory is a modular **Inventory Management System (IMS)** designed to digitize and streamline stock-related operations within a business.  
It replaces manual registers, Excel sheets, and scattered tracking methods with a **centralized real-time inventory management system**.

---

## 🎯 Problem Statement

Many businesses still rely on manual registers or spreadsheets to track inventory. This often results in:

- Data inconsistencies
- Difficulty tracking stock movements
- Delays in warehouse operations
- Lack of real-time visibility of inventory

CoreInventory solves these problems by providing a **centralized platform to manage inventory efficiently**.

---

## 💡 Solution

CoreInventory provides a unified system to manage:

- Product inventory
- Incoming stock
- Outgoing stock
- Internal warehouse transfers
- Inventory adjustments

This helps businesses maintain **accurate stock records and improve operational efficiency**.

---

## ✨ Features

### Product Management
- Create and update products
- Assign SKU / product code
- Manage product categories
- Define units of measure

### Inventory Operations
- Receipts (Incoming goods)
- Delivery Orders (Outgoing goods)
- Internal warehouse transfers
- Inventory adjustments

### Dashboard
- Total products in stock
- Low stock alerts
- Pending receipts
- Pending deliveries
- Inventory movement overview

### Smart Filters
- Filter by warehouse
- Filter by product category
- Filter by document type
- Filter by status

---

## 🧭 Inventory Workflow Example

1. **Receive goods from vendor**
   - Example: Receive 100 units of steel  
   - Stock increases → `+100`

2. **Internal transfer**
   - Move stock from Main Warehouse → Production Rack  
   - Total stock remains the same

3. **Delivery to customer**
   - Deliver 20 units  
   - Stock decreases → `-20`

4. **Stock adjustment**
   - 3 damaged items removed  
   - Stock decreases → `-3`

All movements are recorded in the **inventory ledger**.

---

## 🛠 Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Odoo Framework

### Database
- PostgreSQL

### Tools
- Git
- GitHub
- VS Code

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/jinay378/Odoo-Hackathon.git
```

Go to the project folder

```bash
cd Odoo-Hackathon
```

Install dependencies and start the application.

---

## 📂 Project Structure

```
Odoo-Hackathon
│
├── README.md
├── frontend
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── backend
│   └── app.py
│
├── docs
│   └── system-design.md
│
└── screenshots
    ├── dashboard.png
    ├── products.png
    └── inventory.png
```

---

## 📸 Screenshots

Add screenshots of your application here:

- Dashboard
- Product Management
- Inventory Operations
- Stock Movement

---

## 🔮 Future Improvements

- Barcode scanning support
- Mobile application
- AI-based stock prediction
- Advanced analytics dashboard

---

## 👥 Team Members

- Jinay Shah  
- Parshva Shah 
- Arham Shah  
- Naman Shah  

---

## 📄 License

This project was developed for the **Odoo Hackathon** and is intended for educational purposes.
