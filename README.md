# Crud-Operation
# Laravel CRUD Application: Branch, Category, Product

This is a Laravel-based CRUD application managing three related entities: **Branch**, **Category**, and **Product**. Data is stored in a **MySQL** database.

---

## 📁 Table Structure

### 🏢 Branch Table
| Field | Type         | Description        |
|-------|--------------|--------------------|
| id    | integer (PK) | Primary Key        |
| name  | varchar(255) | Branch name        |
| email | varchar(255) | Branch email       |
| phone | varchar(255) | Branch phone       |
| logo  | varchar(255) | Logo file path     |

### 📂 Category Table
| Field | Type         | Description        |
|-------|--------------|--------------------|
| id    | integer (PK) | Primary Key        |
| name  | varchar(255) | Category name      |

### 📦 Product Table
| Field      | Type          | Description              |
|------------|---------------|--------------------------|
| id         | integer (PK)  | Primary Key              |
| name       | varchar(255)  | Product name             |
| cost       | double(10,2)  | Cost price               |
| price      | double(10,2)  | Selling price            |
| categoryId | integer (FK)  | Foreign key to Category  |
| branchId   | integer (FK)  | Foreign key to Branch    |

---

## ⚙️ Features

- Full CRUD operations for all three tables
- Form validation and file upload (Logo)
- Relational mapping using Eloquent ORM
- Responsive UI using Blade and Bootstrap
- Deployed online with public GitHub repo

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/laravel-crud-branch-category-product.git
cd laravel-crud-branch-category-product

