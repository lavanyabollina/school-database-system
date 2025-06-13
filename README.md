# 🎓 School Database Management System – CSP Project

## 📘 Project Title
**Transforming Government Schools with Advanced Database Solutions**

## 🧾 Description

This project was developed as part of our **Community Service Project (CSP)** with the goal of improving the record-keeping system at government schools. The school previously relied on handwritten records, which led to issues like data loss, delays in issuing certificates, and difficulty retrieving old student data. To resolve these issues, we designed and deployed a simple **web-based database management system**.

## 📍 Project Location
**gudlavalleru-government school**

## 👥 Team Members
- Lavanya Bollina *(Team Leader)*
- keerthi alajangi
- jyoshmitha
- revathi

## 📆 Duration
**june 2024 – nov 2024**

---

## 🚀 Features

- 📋 Add, edit, delete student records  
- 🖼 Upload and manage student images  
- 📂 Easy record retrieval and certificate generation  
- 🔐 Admin dashboard with secure session management  

---

## 🛠️ Technologies Used

| Layer       | Technologies         |
|-------------|----------------------|
| Frontend    | HTML, CSS, JavaScript |
| Backend     | PHP                   |
| Database    | MySQL                 |
| Server      | XAMPP (Apache, MySQL) |

---

## 📁 Project Structure
```
school-database-system/
├── admin/           # Admin pages (add, update, delete students)
├── databaseimg/     # Student image files (JPG, PNG)
├── include/         # Common PHP files like Session and Functions
├── sql/             # SQL dump for creating the database
├── student/         # (If applicable) Student-facing pages
├── README.md        # Project documentation
├── dbcon.php       # Configuration file (DB connection etc.)
├── footer.php        # Homepage or main entry point
├── header.php        # Admin/student login page
├── index.php        # Global styling file
├── login.php  # Common dashboard or redirect logic
```
1. **Clone this repository**
   ```bash
   git clone https://github.com/lavanyabollina/school-database-system.git
   
2.Move to XAMPP directory
```bash
Paste the folder inside htdocs (e.g., C:\xampp\htdocs)

```

3.Start Apache and MySQL using XAMPP Control Panel

4.**Import the SQL file**

-Open http://localhost/phpmyadmin

-Create a new database (e.g., school_db)

-  Import the SQL file from sql/test.sql

5.**Run the project**

Visit http://localhost/school-database-system/admin

**Impact**
- The new system helped the school:

- Digitally maintain all student records

- Save time in issuing documents

- Reduce chances of data loss

- Improve accessibility and transparency

