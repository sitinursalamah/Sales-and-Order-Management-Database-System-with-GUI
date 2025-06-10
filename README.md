# 🛒 Sales & Order Database System with Python & SQLite

This project demonstrates the design and implementation of a **relational database** system to efficiently manage customers, orders, and sales transactions using **SQLite** and **Python**. It also features an **interactive user interface** built in **Google Colab** using `ipywidgets` to facilitate seamless data input, query operations, and checkout simulation with QR code integration.

## 📌 Project Objectives

- To build a structured database for storing and managing sales, customer, and order data.
- To develop an intuitive user interface for data interaction using Google Colab.
- To implement a QR code-based checkout feature for simulating real-world payment workflows.

## ⚙️ Features

### 🔹 Relational Database (SQLite)
- Tables: `Customers`, `Orders`, `Products`,`order_details`,`order_payments`
- Supports foreign key relationships and constraints
- Efficient queries to retrieve and summarize sales data

### 🔹 Interactive UI (Google Colab + ipywidgets)
- Form-like input for adding new customers, products, and orders
- Dropdown-based navigation and search
- Real-time table previews after each transaction

### 🔹 Checkout & QR Code Payment
- Automatically generates QR codes (via `qrcode` library) at checkout
- QR code contains payment information (e.g., transaction ID, total price)
- Designed to simulate real-world transaction systems

## 💻 Technologies Used

| Technology      | Description                                  |
|-----------------|----------------------------------------------|
| Python          | Main programming language                    |
| SQLite          | Lightweight relational database engine       |
| ipywidgets      | For building interactive UI in Colab         |
| qrcode          | For generating QR codes                      |
| pandas          | Data manipulation and display                |

## 🗃️ Database Schema Overview
