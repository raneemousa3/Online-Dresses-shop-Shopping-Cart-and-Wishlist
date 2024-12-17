
# 🛒 Online Dresses Shopping Cart and Wishlist

## 📖 Overview
The **Online Dresses Shopping Cart and Wishlist** is a C++ application that simulates an online shopping experience for dresses. Users can manage their shopping cart and wishlist by adding, viewing, and removing products while calculating total costs. This project demonstrates object-oriented programming principles, such as inheritance, polymorphism and linked lists.

---

## ✨ Features
- **Shopping Cart**:
  - Add dresses, skirts, tops, and accessories to the cart ****addProduct()****
  - View all items with details (price, size, color, etc.) ****viewItems()****
  - Calculate the total price of all items in the cart. ****calculateTotal()*****
  - Update or reduce item quantities.    ****reduceQuantity()****
  - Remove items from the cart.  ****removeItem****

- **Wishlist**:
  - Save favorite items for future consideration. ****MovetoWishlist()****
  - Move items from the wishlist to the cart.  ****MovetoShoppingCart()****

- **Product Management**:
  - Manage multiple product types (dresses, skirts) using inheritance. 
  - Move Products between the shopping cart and wishlist 
  - Attributes include name, price, size, color, and quantity.

📦 **UML Diagram**
-------------------------
![Blank diagram (3)](https://github.com/user-attachments/assets/10fb2da7-980f-48c8-8de1-c3380a664e8a)

---

##  🎯  In Process
Add a graphical user interface (GUI) for a better user experience.

## 🏗️ Project Structure
This project uses a modular design, separating logic into manageable components:


```plaintext
📂 OnlineDressesShopping
├── 📄 main.cpp         # Entry point of the application
├── 📄 Product.h        # Header file for the base Product class
├── 📄 Product.cpp      # Implementation of Product methods
├── 📄 Tops.h           # Header file for the base Tops class
├── 📄 Tops.cpp         # Implementation of Tops methods
├── 📄 Dress.h          # Header file for the child Dress class
├── 📄 Dress.cpp        # Implementation of child class Dress
├── 📄 skirts.h         # Header file for the child skirts class
├── 📄 skirt.cpp        # Implementation of child Skirt class
├── 📄 Accessories.h    # Header file for the child Accessories class
├── 📄 Accessories.cpp  # Implementation of child Accessories class
├── 📄 cart.h           # Header file for the parent Cart class
├── 📄 cart.cpp         # Implementation of parent Cart methods
├── 📄 ShoppingCart.h   # Header file for the ShoppingCart class
├── 📄 ShoppingCart.cpp # Implementation of ShoppingCart methods
├── 📄 Wishlist.h       # Header file for the Wishlist class
├── 📄 Wishlist.cpp     # Implementation of Wishlist methods
└── 📄 README.md        # Project documentation

