
# 🛒 Online Dresses Shopping Cart and Wishlist

## 📖 Overview
The **Online Dresses Shopping Cart and Wishlist** is a C++ application that simulates an online shopping experience for dresses. Users can manage their shopping cart and wishlist by adding, viewing, and removing products while calculating total costs. This project demonstrates object-oriented programming principles, such as inheritance and polymorphism.

---

## ✨ Features
- **Shopping Cart**:
  - Add dresses and skirts to the cart.
  - View all items with details (price, size, color, etc.).
  - Calculate the total price of all items in the cart.
  - Update or reduce item quantities.
  - Remove items from the cart.

- **Wishlist**:
  - Save favorite items for future consideration.
  - Move items from the wishlist to the cart.

- **Product Management**:
  - Manage multiple product types (dresses, skirts) using inheritance.
  - Move Products between the shopping cart and wishlist 
  - Attributes include name, price, size, color, and quantity.
    
##  🎯  In Process
Add a graphical user interface (GUI) for a better user experience.
![Blank diagram (3)](https://github.com/user-attachments/assets/10fb2da7-980f-48c8-8de1-c3380a664e8a)

---

## 🏗️ Project Structure
This project uses a modular design, separating logic into manageable components:


```plaintext
📂 OnlineDressesShopping
├── 📄 main.cpp         # Entry point of the application
├── 📄 Product.h        # Header file for the base Product class
├── 📄 Product.cpp      # Implementation of Product methods
├── 📄 ShoppingCart.h   # Header file for the ShoppingCart class
├── 📄 ShoppingCart.cpp # Implementation of ShoppingCart methods
├── 📄 Wishlist.h       # Header file for the Wishlist class
├── 📄 Wishlist.cpp     # Implementation of Wishlist methods
└── 📄 README.md        # Project documentation

