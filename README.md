#  HomeCook – Home-Cooked Food Delivery Application

**HomeCook** is an online food ordering platform that connects customers with fresh, home-cooked meals.  
This application allows users to browse the daily menu, place customized food orders, and get meals delivered to their doorstep.

---

##  Project Overview

HomeCook provides an easy way for users to order home-cooked food with flexible serving sizes and timely delivery.  
This project is built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js).

---

##  Features

###  Home Page
- Displays all available food items for the current day.  
- The menu changes every day (dynamic menu system).
- Each food item includes:
  -  Picture
  -  Price
  -  Number of persons a single serving can serve.

###  Food Ordering
- Customers can select the number of persons to order for (e.g., 1, 2, 3, etc.).
- Orders must be placed **at least 5 hours before** the desired delivery time.

###  Checkout & Pricing
- The system automatically calculates:
  - Total cost based on the **serving size** and **number of persons**.
- Example: If 1 serving serves 2 persons and the customer orders for 4, the total will be `2 × price`.

### Delivery Details
- The system asks for a delivery address at checkout.
- Orders are stored in the database with all details (items, quantity, price, and address).

---

##  Tech Stack

| Layer | Technology Used |
|--------|------------------|
| **Frontend** | React.js, HTML, CSS, JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose ORM) |
| **Styling** | Tailwind CSS / Bootstrap (optional) |
| **API Testing** | Postman (for backend routes) |

---



