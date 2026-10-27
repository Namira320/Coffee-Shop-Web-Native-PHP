# ☕ Classic Coffee Web Native

<p align="center">
  <b>A Digital Platform Coffee Shop Transaction System Based on Web</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

---

## 📖 Project Background
In the era of rapid digitalization, the Food and Beverage (F&B) industry demands businesses to adapt online. **Classic Cafe**, which carries a traditional and cozy atmosphere, faces challenges in reaching a broader audience and streamlining its operational processes. 

This website was built as a solution to bridge the cafe's classic charm with modern consumer expectations—functioning as a digital catalog, transactional platform, and inventory management tool for the cafe administrator.

---

## 🛠️ Tech Stack & Architecture
The system is designed using a modular architecture that separates the customer frontend and the admin backend:
- **Programming Languages:** PHP (PDO Extension), JavaScript, HTML5, CSS3
- **Database Management:** MySQL / phpMyAdmin
- **Local Server:** XAMPP
- **Code Editor:** Visual Studio Code

### 🗄️ Database Relationship Structure (`db_kantin`)
The system database consists of 5 main entities:
1. **`user`**: Manages user accounts, staff data, and access levels (admin/employee/user).
2. **`menu_produk`**: Stores the product catalog (Coffee, Non-Coffee, Pastry) along with prices, descriptions, and images.
3. **`kantin_pesanan`**: Records customer orders along with order statuses (*New, Processing, Completed*).
4. **`desain_pesanan`**: Stores custom design data or special order notes.
5. **`kantin_pesan_kontak`**: Houses messages or feedback sent by customers through the contact form.

---

## 🖥️ Documentation 

| Feature | Description |
| :--- | :--- |
| **Home Page** | Main page featuring the modern hero banner of Classic Coffee. |
| **About Us** | Information page detailing the profile, dedication, and background of the coffee shop. |
| **Our Menu** | Catalog of coffee, non-coffee, and pastry products with dynamic filters. |
| **Product Details & Cart** | Pop-up menu details and management of customer shopping items. |
| **Contact Page** | Customer feedback form integrated with Google Maps. |

*(Note: You can adjust the image folder paths above if you move them to a dedicated screenshot asset directory).*

---

## ⚙️ Installation Guide

1. **Clone this repository** or download the ZIP file to your local computer.
2. Move the project folder to your local web server directory (e.g., `htdocs` in XAMPP).
3. Start the **Apache** and **MySQL** services via the XAMPP control panel.
4. Open **phpMyAdmin** through your browser (`http://localhost/phpmyadmin`).
5. Create a new database named `db_kantin` and import the required table structure.
6. Configure the database connection in the `config/database.php` file if necessary.
7. Run the project through your browser by accessing:
   ```text
   http://localhost/project-folder-name/
