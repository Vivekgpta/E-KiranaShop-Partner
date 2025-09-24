# 🛠️ E-Kirana Shop | Admin Panel

This document covers the **Admin side of E-Kirana Shop**, a Blinkit-inspired e-commerce platform for a local shop.  
The Admin panel allows the shop owner to **manage products, categories, inventory, and orders** efficiently.

---

## 🚀 Tech Stack

### Backend (Spring Boot)
- RESTful APIs for admin operations
- Spring Security + JWT Authentication (Admin role)
- Spring Data JPA for database interaction
- Validation, Exception Handling & Logging
- Swagger for API documentation

### Frontend (React.js)
- Admin Dashboard UI
- Axios for API calls
- Context API / Redux for state management
- Tailwind CSS for styling
- Responsive design

### Database (SQL)
- MySQL / PostgreSQL
- Tables used: Users, Products, Categories, Orders, Order_Items, Payments
- Proper relationships & foreign keys

---

## 📌 Admin Features

### Product Management
- **Add Product** → Add new items with name, price, stock, category, image.
- **Update Product** → Modify existing product details.
- **Delete Product** → Remove products from inventory.
- **View Products** → Paginated list of all products.

### Category Management
- **Add Category** → Create new product categories.
- **Update Category** → Rename or modify categories.
- **Delete Category** → Remove unused categories.

### Order Management
- **View Orders** → List of all orders placed by users.
- **Update Order Status** → Pending → Processing → Delivered.
- **View Order Details** → Includes user info, items, and payment details.

### Inventory Management
- Track **stock availability** for each product.
- Receive notifications when stock is low (optional future feature).

### User Management (Optional)
- View registered users.
- Manage roles (Customer / Admin).

---

## 🔗 System Architecture (Admin Perspective)

```text
[ React Admin Dashboard ]  --->  [ Spring Boot Admin APIs ]  --->  [ SQL Database ]
       (UI/UX)                    (Business Logic)              (Data)
```

## Hey, I'm Vivek Gupta.

Thankyou
