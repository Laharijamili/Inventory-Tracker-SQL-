# Inventory-Tracker-SQL

## 📌 Intern Details
* **Domain:** Full Stack Web Development
* **Intern ID:** CITS2364
* **Name:** Jamili Lahari
* **Duration:** 6 Weeks
* **Organization:** CodTech IT Solutions

## 🚀 Project Overview
A robust Full Stack Inventory Management System engineered to track, organize, and manage product stock levels efficiently. The system utilizes a structured relational database architecture to manage product entries, monitor stock updates, record transaction details, and maintain an organized supply chain pipeline.

## ✨Project scope (Features)
* **Inventory Dashboard:** Real-time visual overview of total stock counts, categories, and total inventory value.
* **CRUD Stock Control:** Seamlessly Create, Read, Update, and Delete inventory items with precise quantity attributes.
* **Low Stock Notification:** Automated trigger alerts flag items dropping below a defined threshold to prevent stockouts.
* **Categorized Management:** Logical database schemas partition inventory into distinct item categories and subcategories.
* **Transaction History Logs:** Auto-generates log reports tracking every incoming stock addition and outgoing deduction.

## 🛠️ Tech Stack
* **Frontend:** React, Tailwind CSS, JavaScript (ES6)
* **Backend:** Node.js, Express.js
* **Database:** MySQL / PostgreSQL (SQL Relational Database)
* **ORM / Driver:** Sequelize / `mysql2`

## 🏃 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Inventory-Tracker-SQL
   ```

2. **Set up the SQL Database:**
   * Open your SQL CLI client or UI tool (such as MySQL Workbench or pgAdmin).
   * Create a new relational database instance named `inventory_db`.
   * Import or run the provided schema definitions to populate tables:
     ```sql
     SOURCE database/schema.sql;
     ```

3. **Set up the backend server:**
   ```bash
   cd backend
   npm install
   ```
   * Create a `.env` file in the root of your `backend` directory and add your credentials:
     ```env
     PORT=5000
     DB_HOST=localhost
     DB_USER=your_sql_username
     DB_PASS=your_sql_password
     DB_NAME=inventory_db
     ```
   * Launch the API server environment:
     ```bash
     npm start
     ```

4. **Set up the frontend application:**
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

5. **Access the application:**
   * Open your browser and navigate directly to `http://localhost:3000`.
