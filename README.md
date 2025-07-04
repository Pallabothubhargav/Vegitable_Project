# Vegitable_Project

# 🛒 Inventory Management System (Vegetable Shop)

A simple **command-line based inventory management system** written in Python. This project supports **two roles**: **Owner** and **User**. Owners can manage inventory, while users can buy vegetables using a cart system.

---

## 📌 Features

### 👨‍💼 Owner:
- Secure login (hardcoded)
- Add new vegetable items
- Remove existing items
- Update quantities and prices
- View current inventory
- View revenue and profit report

### 👤 User:
- Add vegetables to cart
- Remove vegetables from cart
- Modify quantities
- View current cart
- Generate bill (includes revenue and profit update)
- Automatically clears cart after billing

---

## 🗂️ Project Structure

- Inventory is managed using **parallel lists**:
  - `veg` – list of vegetables
  - `quty` – quantities (kg)
  - `costprice` – cost prices
  - `sellingprice` – selling prices
- Cart is also managed using two lists:
  - `user_cart` – items added by the user
  - `user_quant` – corresponding quantities
- `report` list stores transaction summaries (for revenue/profit report)

---

## 🔐 Owner Login

```python
Name: Bhargav
Password: 2003
