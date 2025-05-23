# 🛒 Cloud Mart - E-Commerce Website

## 🔧 How to Run the Project (Using PHP and MySQL)

### ✅ 1. Download and Extract
- Download the `.zip` file of the project.
- Extract it and locate the folder named `Cloud Mart`.

### ✅ 2. Move to Web Server Directory
Paste the `Cloud Mart` folder inside your local server's root directory:

- For **XAMPP**: `C:/xampp/htdocs`
- For **WAMP**: `C:/wamp/www`
- For **LAMP (Linux)**: `/var/www/html`

### ✅ 3. Setup the Database
1. Open PHPMyAdmin: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
2. Create a **new database** named: **Cloud Mart3**
3. Click the **Import** tab.
4. Import the `.sql` file located inside the `SQL file` folder from the extracted project.

### ✅ 4. Run the Application
- **User Panel:**  
[http://localhost/Cloud Mart/User Panel](http://localhost/Cloud%20Mart/User%20Panel)

- **Admin Panel:**  
[http://localhost/Cloud Mart/User Panel/admin](http://localhost/Cloud%20Mart/User%20Panel/admin)

> ⚠️ Tip: Rename the folder to `cloud_mart` to avoid issues with URLs that contain spaces.

---

## 🔐 Login Credentials ✅

### 👤 User
- **Username:** `savi.user@gmail.com`
- **Password:** `ASDF@1234`

### 🔒 Admin
- **Username:** `admin`
- **Password:** `Test@123`

---

## 📂 Folder Structure

~~~
Cloud Mart/
├── User Panel/
│   ├── admin/
│   ├── assets/
│   └── index.php
├── SQL file/
│   └── cloud_mart.sql
└── README.md
~~~


---

## 📌 Notes
- Make sure Apache and MySQL services are running (via XAMPP/WAMP/LAMP).
- Compatible with PHP 7.x / 8.x.
- Default database user is `root` with no password (for XAMPP).

---
