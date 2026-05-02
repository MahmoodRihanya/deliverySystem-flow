# 🍔 Food Delivery System

A full-stack food delivery platform built with **Flutter** & **Node.js/Express**,
consisting of three mobile apps, a restaurant owner app, and an admin web dashboard — all connected to a shared backend.

---

## 📱 Apps Overview

| App | Platform | Description |
|-----|----------|-------------|
| 🛒 Customer App | Flutter Mobile | Browse restaurants, place orders, track delivery in real-time |
| 🚗 Driver App | Flutter Mobile | Accept orders, go to customer, confirm delivery |
| 🍽️ Restaurant Owner App | Flutter Mobile | Manage menu, meals, offers, and incoming orders |
| 🖥️ Admin Dashboard | Flutter Web | Manage users, restaurants, drivers, categories, and analytics |

---

## 🛠️ Tech Stack

**Frontend:** Flutter (Mobile & Web)  
**Backend:** Node.js / Express  
**Database:** MySQL + Sequelize  
**Realtime:** Socket.IO  
**Notifications:** Firebase FCM  
**Auth:** JWT  

---

## 📸 App Screens & Flow

---

## 🔐 Auth Flow — Customer & Driver

### 1️⃣ Splash

| | Splash | | |
|-|--------|---|--|
| | <img src="screens/auth_driver_and_customer/splash.jpg" width="220"/> | ➡️ Login | ➡️ Register |

---

### 2️⃣ Login & Register

| Login | | Register |
|-------|---|----------|
| <img src="screens/auth_driver_and_customer/login.jpg" width="220"/> | | <img src="screens/auth_driver_and_customer/register.jpg" width="220"/> |

---

### 3️⃣ Login Flow

| Login | → | OTP | → | Home |
|-------|---|-----|---|------|
| <img src="screens/auth_driver_and_customer/login.jpg" width="220"/> | ➡️ | <img src="screens/auth_driver_and_customer/input_otp_code.jpg" width="220"/> | ➡️ | <img src="screens/customer/home.jpg" width="220"/> |

| Login | → | Reset Password | → | OTP | → | Home |
|-------|---|----------------|---|-----|---|------|
| <img src="screens/auth_driver_and_customer/login.jpg" width="220"/> | ➡️ | <img src="screens/auth_driver_and_customer/reset_password.jpg" width="220"/> | ➡️ | <img src="screens/auth_driver_and_customer/input_otp_code.jpg" width="220"/> | ➡️ | <img src="screens/customer/home.jpg" width="220"/> |

---

### 4️⃣ Register Flow

| Register | → | OTP | → | Home |
|----------|---|-----|---|------|
| <img src="screens/auth_driver_and_customer/register.jpg" width="220"/> | ➡️ | <img src="screens/auth_driver_and_customer/input_otp_code.jpg" width="220"/> | ➡️ | <img src="screens/customer/home.jpg" width="220"/> |

---

## 🛒 Customer App Flow

### 🏠 Home

| Home | | Home (Scrolled) |
|------|---|-----------------|
| <img src="screens/customer/home.jpg" width="220"/> | | <img src="screens/customer/home2.jpg" width="220"/> |

---

### 🔍 Search & Browse

| Category Search | → | Meal Search | → | Restaurant Details |
|----------------|---|-------------|---|-------------------|
| <img src="screens/customer/category_search.jpg" width="220"/> | ➡️ | <img src="screens/customer/meal_search.jpg" width="220"/> | ➡️ | <img src="screens/customer/restaurante_details.jpg" width="220"/> |

| Restaurants Offers | → | Meal Details |
|-------------------|---|--------------|
| <img src="screens/customer/restaurants_offer.jpg" width="220"/> | ➡️ | <img src="screens/customer/meal_details.jpg" width="220"/> |

---

### 🛒 Cart & Checkout

| Meal Details | → | Cart | → | Address |
|-------------|---|------|---|---------|
| <img src="screens/customer/meal_details.jpg" width="220"/> | ➡️ | <img src="screens/customer/cart_bottom_sheet.jpg" width="220"/> | ➡️ | <img src="screens/customer/address_bottom_sheet.jpg" width="220"/> |

---

### 📦 Orders & Tracking

 | Active Orders | → | Order Details | → | Track Driver |
|--------------|---|---------------|---|--------------|
| <img src="screens/customer/active_orders.jpg" width="220"/> | ➡️ | <img src="screens/customer/order_details.jpg" width="220"/> | ➡️ | <img src="screens/customer/location_driver.jpg" width="220"/> |


| Delivered Orders |  → | Rate Restaurant | → | Rate Driver |
|-----------------|---|-------------|---|----------------|
| <img src="screens/customer/delivered_orders.jpg" width="220"/> |➡️ | <img src="screens/customer/restaurant_rating.jpg" width="220"/> | ➡️ | <img src="screens/customer/driver_rating.jpg" width="220"/> | 


---
### Addresses
| My Addresses |  → | New Address | → | New Address Details |
|-----------------|---|-------------|---|----------------|
| <img src="screens/customer/my_addresses.jpg" width="220"/> |➡️ | <img src="screens/customer/input_address_location.jpg" width="220"/> | ➡️ | <img src="screens/customer/address_datails_bottom_sheet.jpg" width="220"/> | 

| My Addresses |  → | Address Location | 
|-----------------|---|-------------|
| <img src="screens/customer/my_addresses.jpg" width="220"/> |➡️ | <img src="screens/customer/address_location_on_map.jpg" width="220"/>



---
### Favorites
| Restaurants |  → | Addresses | → | Meals |
|-----------------|---|-------------|---|----------------|
| <img src="screens/customer/favorite_restaurante.jpg" width="220"/> |➡️ | <img src="screens/customer/favorite_addresses.jpg" width="220"/> | ➡️ | <img src="screens/customer/favorite_meals.jpg" width="220"/> | 

---

### 👤 Profile & Settings

| Profile | → | Help & Support |
|---------|---|--------------|
| <img src="screens/customer/profile.jpg" width="220"/> | ➡️ | <img src="screens/customer/Help_and_support.jpg" width="220"/> |

---




## 🚗 Driver App Flow

### 🏠 Home

| Available | | Not Available |
|-----------|---|---------------|
| <img src="screens/driver/home_available.jpg" width="220"/> | | <img src="screens/driver/home_not_available.jpg" width="220"/> |

---

### 📦 Order Flow

| New Order Request | → | Navigate to Customer |
|------------------|---|----------------------|
| <img src="screens/driver/new_order.jpg" width="220"/> | ➡️ | <img src="screens/driver/location_driver.jpg" width="220"/> |

---

### 👤 Profile

| Profile |
|---------|
| <img src="screens/driver/profile.jpg" width="220"/> |

---

## 🍽️ Restaurant Owner App Flow

### 🔐 Auth

| Splash | → | Login | | Register |
|--------|---|-------|---|----------|
| <img src="screens/owner/splash.jpg" width="220"/> | ➡️ | <img src="screens/owner/login.jpg" width="220"/> | | <img src="screens/owner/register.jpg" width="220"/> |

### 📋 Register Restaurant

| Register | → | Restaurant Info | → | Restaurant Location |
|------|---|--------|---|--------------|
| <img src="screens/owner/register_restaurante_info.jpg" width="220"/> | ➡️ | <img src="screens/owner/register_restaurante_info.jpg" width="220"/> |  ➡️ | <img src="screens/owner/map.jpg" width="220"/> | 

---
### Restaurant Info

| Home | → | Restaurant Info | → |Restaurant Info (Scrolled) |
|------|---|--------|---|--------------|
| <img src="screens/owner/home.jpg" width="220"/> | ➡️ | <img src="screens/owner/restaurant_info1.jpg" width="220"/> | ➡️ | <img src="screens/owner/restaurante_info2.jpg" width="220"/> |

| Order Details | 
|--------------|
| <img src="screens/owner/order_details.jpg" width="220"/> | 

---


### 🏠 Home & Orders

| Home | → | Orders | → | Accept Order |
|------|---|--------|---|--------------|
| <img src="screens/owner/home.jpg" width="220"/> | ➡️ | <img src="screens/owner/orders.jpg" width="220"/> | ➡️ | <img src="screens/owner/accept_order.jpg" width="220"/> |

| Order Details | 
|--------------|
| <img src="screens/owner/order_details.jpg" width="220"/> | 

---

### 🍕 Meals Management

| Meals | → | Add Meal | / | Edit Meal |
|-------|---|----------|---|-----------|
| <img src="screens/owner/meals.jpg" width="220"/> | ➡️ | <img src="screens/owner/add_meal.jpg" width="220"/> | | <img src="screens/owner/edite_meal.jpg" width="220"/> |

---

### 📊 Offers & Statistics

| Offers | | Statistics |
|--------|---|-----------|
| <img src="screens/owner/offers.jpg" width="220"/> | | <img src="screens/owner/statistics.jpg" width="220"/> |

---

## 🖥️ Admin Dashboard (Flutter Web)

### 🔐 Login

| Login |
|-------|
| <img src="screens/dashboard/login.jpg" width="600"/> |

---

### 🏠 Home & Overview

| Dashboard Home |
|---------------|
| <img src="screens/dashboard/home.jpg" width="600"/> |

---

### 📂 Management Screens

| Orders | | Drivers |
|--------|---|---------|
| <img src="screens/dashboard/orders.jpg" width="400"/> | | <img src="screens/dashboard/drivers.jpg" width="400"/> |

| Categories | → | Edit Category |
|-----------|---|---------------|
| <img src="screens/dashboard/categories.jpg" width="400"/> | ➡️ | <img src="screens/dashboard/edite_category.jpg" width="400"/> |

| Offers | | Settings |
|--------|---|---------|
| <img src="screens/dashboard/offers.jpg" width="400"/> | | <img src="screens/dashboard/settings.jpg" width="400"/> |

| Settings (continued) |
|---------------------|
| <img src="screens/dashboard/settings2.jpg" width="600" high="100" alt="Arabic dashboard settings page showing system settings form with welcome message, delivery price, expected delivery time, driver assignment timeout and save settings button in a pastel pink admin interface"/> |

---

## 🔔 Global Screens (Shared across apps)

| Notifications | Notifications Screen | Messages |
|--------------|---------------------|----------|
| <img src="screens/global/notification.jpg" width="220"/> | <img src="screens/global/notifications_screen.jpg" width="220"/> | <img src="screens/global/message.jpg" width="220"/> |

---

## 👨‍💻 Developer

Built with ❤️ using Flutter & Node.js
