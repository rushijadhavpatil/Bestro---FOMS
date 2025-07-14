# Bestro - FOMS 🍽️
Foood Order Management System Using Django
Welcome to **Bestro**, an online food ordering and management system specializing in door-to-door deliveries. This web application is developed using **Django**, **HTML**, **CSS**, and **JavaScript**.

---

## 🚀 Features

- 🔐 Google Sign-In for customers (no need to remember passwords)
- 📦 Real-time stock updates after each order
- ⭐ Customer feedback with dynamic item rating updates
- ⚡ Asynchronous item filters for a smooth browsing experience
- ⏱️ Smart delivery time estimation based on active orders
- 📧 Email notifications for new offers
- 📊 Staff access to daily sales in downloadable spreadsheet format
- 👨‍🍳 Separate dashboards for customers and staff
- 🌱 Vegan item indicators for conscious eating
- And many more...

---

## 🔧 Getting Started (Local Setup)

Follow the steps below to run the project on your local machine.

### 1. Fork & Clone the Repository

```
git clone https://github.com/{your_username}/Bestro---FOMS.git
cd Bestro---FOMS
```

### 2. Create and Activate Virtual Environment

```
virtualenv myenv --python=python3.6
source myenv/bin/activate
```

### 3. Install Dependencies

```
pip install -r requirements.txt
```

### 4. Setup the Database

```
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the Server

```
python manage.py runserver
```

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to use the application locally.

---

## 🧑‍🍳 How to Use the Website

### 1. Register / Login

* Click on **Sign Up** to register a new customer.
* You can either fill in the form or use **Google Sign-In**.
* After logging in, complete your profile.

### 2. Browse the Menu

* Navigate to **Menu** from the navbar.
* Food items are categorized (6 categories).
* View item name, image, price, description, ratings, and vegan status.
* Use checkboxes to filter by category.

### 3. Place an Order

* Click on **Place Order** to begin.
* Select quantity for each item.
* Click **Add Items** in the sidebar to add to your current order.
* Once ready, click **Finalize**.
* View expected delivery time based on current load.

### 4. Order Delivery

* When your order is received, click **Order Received** on the summary page.

### 5. Provide Feedback

* After confirming delivery, give feedback on each item ordered.
* Ratings will update dynamically.

### 6. View Past Orders

* Click **Past Orders** to view order history.

---

## 🛠️ Staff / Admin Features

Staff have access to additional functionalities.

### 👨‍💼 Default Admin Credentials

```
Username: sd
Password: admin
```

> New staff can only be created by existing staff members.

### 📋 Register a New Staff Member

1. Go to **Register New Employee** in navbar.
2. Fill in the employee form.
3. Submit to create a new staff account.

### 🍲 Manage Menu Items

* Click **Menu**.
* Use **Create New Item** or **Update Item** for management.

### 📈 View Daily Sales

* Visit the **Staff Dashboard** via your profile.
* Click **View Sales** to download sales data as a spreadsheet.

### 📨 Send New Offers

* Navigate to **New Offer**.
* Fill in offer details and click **Publish**.
* Offer will be emailed to all customers.

---

## 🧑‍💻 Developer Notes

* Backend is completely developed from scratch using Django.
* Frontend templates adapted from **templatemo** with necessary modifications.

---

## 📬 Feedback & Contributions

Feel free to fork, explore, and raise PRs or issues!
Suggestions for improvements are always welcome.

---

## 📎 Repository

[https://github.com/rushijadhavpatil/Bestro---FOMS](https://github.com/rushijadhavpatil/Bestro---FOMS)

---

© 2025 Bestro. All rights reserved.

