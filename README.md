# ☁️ Cloud Inventory Management System

A modern **Cloud Inventory Management System** designed to help organizations manage products, stock quantities, suppliers, pricing, and low-stock alerts through a centralized dashboard.

The project is developed as a frontend prototype using **HTML, CSS, and JavaScript**. Product data is currently stored using browser `localStorage`. The application can later be connected to AWS services such as **Amazon DynamoDB, AWS Lambda, API Gateway, Amazon Cognito, and AWS Amplify** to create a fully cloud-based inventory platform.

---

## 🌌 Project Overview

Managing inventory manually can make it difficult to track product quantities, identify low-stock products, and maintain supplier information.

**Cloud Inventory** provides a simple dashboard where users can:

* Add products
* Edit product information
* Delete products
* Search inventory
* Filter products by category
* Monitor stock quantities
* Identify low-stock products
* Track inventory value
* View category-wise stock information
* Manage supplier details

---

## ✨ Features

### 📊 Dashboard

Displays important inventory information:

* Total Products
* Total Stock
* Low Stock Products
* Total Inventory Value

### 📦 Product Management

Users can:

* Add new products
* Edit existing products
* Delete products
* View product details
* Set minimum stock levels

### 🔍 Search

Search products by:

* Product name
* Category
* Supplier

### 🏷️ Category Filtering

Products can be filtered into:

* Electronics
* Stationery
* Furniture
* Accessories

### ⚠️ Low Stock Monitoring

The system automatically identifies products whose stock quantity reaches or falls below the configured minimum stock level.

### 📈 Stock Overview

The dashboard provides a visual category-wise overview of available stock.

### 💾 Data Persistence

The prototype uses browser `localStorage` to preserve inventory data even after refreshing the page.

---

## 🎨 UI Theme

The project uses a **Purple Futuristic / Glassmorphism** design.

### Theme Elements

* Dark purple background
* Violet gradients
* Neon-style buttons
* Glass-inspired cards
* Modern dashboard
* Responsive layout
* Minimal inventory interface

---

## 🛠️ Technologies Used

| Technology   | Purpose                         |
| ------------ | ------------------------------- |
| HTML5        | Website structure               |
| CSS3         | UI design and responsive layout |
| JavaScript   | Application logic               |
| LocalStorage | Prototype data storage          |
| AWS          | Proposed cloud deployment       |
| DynamoDB     | Proposed cloud database         |
| Lambda       | Proposed backend                |
| API Gateway  | Proposed API layer              |
| Cognito      | Proposed authentication         |

---

## ☁️ Proposed AWS Architecture

```text
                    USER
                      │
                      ▼
              AWS Amplify / CloudFront
                      │
                      ▼
              HTML + CSS + JavaScript
                      │
                      ▼
                API Gateway
                      │
                      ▼
                 AWS Lambda
                      │
                      ▼
                 DynamoDB
                      │
              ┌───────┴───────┐
              ▼               ▼
          Inventory       Supplier Data
              │
              ▼
         Cloud Dashboard
```

---

## 🔄 Application Workflow

```text
Login
  ↓
Dashboard
  ↓
View Inventory
  ↓
Add / Edit Product
  ↓
Enter Stock Details
  ↓
Save Product
  ↓
Update Inventory
  ↓
Check Stock Level
  ↓
Low Stock Alert
```

---

## 📁 Project Structure

```text
CloudInventory/
│
├── index.html
│
└── README.md
```

---

## 💻 How to Run the Project

### Step 1: Create the project folder

Create a folder named:

```text
CloudInventory
```

### Step 2: Open in VS Code

Open the folder in Visual Studio Code.

### Step 3: Create the HTML file

Create:

```text
index.html
```

Paste the complete project code into the file.

### Step 4: Run the project

You can simply open `index.html` in a browser.

For a better development experience, install the **Live Server** extension in VS Code.

Then:

```text
Right Click index.html
        ↓
Open with Live Server
```

The project will open in your browser.

---

## 🧪 Sample Products

The project includes sample inventory data such as:

| Product              | Category    | Stock |  Price |
| -------------------- | ----------- | ----: | -----: |
| Wireless Keyboard    | Electronics |    32 | ₹1,299 |
| USB-C Hub            | Electronics |     8 |   ₹899 |
| Notebook Pack        | Stationery  |    65 |   ₹250 |
| Office Chair         | Furniture   |    14 | ₹5,499 |
| Bluetooth Headphones | Accessories |     4 | ₹1,999 |

---

## 💾 Current Data Storage

The current version uses:

```text
Browser LocalStorage
```

The inventory is saved under:

```text
cloudInventoryProducts
```

This makes the project easy to run without setting up a database.

**Important:** This is a prototype implementation. The data is stored locally in the user's browser and is not yet synchronized between multiple users or devices.

---

## ☁️ Future Cloud Implementation

The prototype can be upgraded into a real cloud application using AWS.

### Amazon Cognito

Used for:

* User registration
* Login
* Authentication
* User management

### Amazon API Gateway

Used to provide APIs for:

* Adding products
* Updating products
* Deleting products
* Retrieving inventory

### AWS Lambda

Used as the backend business logic layer.

### Amazon DynamoDB

Used to store:

* Product information
* Stock quantities
* Supplier information
* Pricing
* Minimum stock levels

### AWS Amplify

Can be used to host and deploy the frontend application.

---

## 🚀 Future Enhancements

Possible improvements include:

* 🔐 User authentication
* ☁️ Real-time cloud synchronization
* 📊 Advanced inventory charts
* 📧 Low-stock email notifications
* 📱 Mobile-friendly PWA
* 📥 CSV import
* 📤 CSV/PDF export
* 🧾 Invoice management
* 🏪 Supplier management
* 📦 Purchase order management
* 📈 Inventory history
* 👥 Multiple user roles
* 🔄 Real-time stock updates
* 🔔 Automated notifications
* 🤖 AI-based demand prediction

---

## 🎯 Project Objectives

The main objectives of this project are:

1. To develop a simple inventory management platform.
2. To monitor product stock efficiently.
3. To identify low-stock products automatically.
4. To maintain supplier and product information.
5. To calculate total inventory value.
6. To understand cloud application architecture.
7. To demonstrate how a local prototype can be migrated to AWS cloud services.

---

## 🎓 Academic Use

This project can be used as a **Cloud Computing Mini Project** for demonstrating:

* Cloud application architecture
* Frontend development
* Data management
* Inventory management
* AWS service integration
* Serverless architecture concepts
* Database concepts
* Responsive web design

---

## 👩‍💻 Developer

**Charulatha S**

B.E. Computer Science Engineering
Prathyusha Engineering College

---

## 📄 License

This project is created for **educational and academic purposes**.

You are free to modify and improve the project for learning and college project demonstrations.
