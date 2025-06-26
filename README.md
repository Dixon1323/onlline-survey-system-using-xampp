# Online Survey System using XAMPP

[![Language](https://img.shields.io/badge/Language-JavaScript-yellow.svg?style=for-the-badge)](https://en.wikipedia.org/wiki/Programming_language)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)](https://github.com/YOUR_USERNAME/onlline-survey-system-using-xampp/graphs/commit-activity)

An online survey system designed to work within a local XAMPP environment. This web-based application allows users to create, manage, and answer surveys. It provides separate interfaces for administrators and regular users.

> ⚠️ **Note:** I'm not a professional JavaScript developer. I completed this project with the help of **YouTube tutorials**, **GitHub repositories**, and **Stack Overflow** discussions. It's a learning project and any constructive feedback or contribution is welcome!

---

## 📑 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## ✅ Features

Based on the current implementation and structure, the system includes:

- User Authentication (Login System)
- Admin Panel with survey management features (`admin_class.php`)
- Survey Creation and Editing (`edit_survey.php`)
- Ability to Answer Surveys (`answer_survey.php`)
- Database Integration (`db_connect.php`)
- AJAX-based Dynamic Content Handling (`ajax.php`)

---

## 🛠 Technologies Used

- **JavaScript** (Frontend logic)
- **PHP** (Backend processing)
- **MySQL** (Database management)
- **HTML & CSS** (UI and styling)
- **XAMPP** (Development environment: Apache + MySQL + PHP + phpMyAdmin)

---

## 🖥 Installation

This project is intended to run in a local environment using XAMPP or an equivalent PHP development stack.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/onlline-survey-system-using-xampp.git
```

### Step 2: Move to Web Server Directory

Copy the cloned folder into your XAMPP installation directory, typically under:

```
C:\xampp\htdocs\
```

### Step 3: Setup the Database

1. Launch **XAMPP** and start **Apache** and **MySQL**.
2. Visit `http://localhost/phpmyadmin`.
3. Create a new database (e.g., `survey_db`).
4. Import the SQL schema file if provided (look for a file like `database.sql` in the project folder).  
   *If a `.sql` file is missing, you'll need to manually create the required tables.*

### Step 4: Configure Database Connection

Edit the file `db_connect.php` to match your local setup:

```php
$host = "localhost";
$username = "root";
$password = "";
$database = "survey_db"; // Use your database name
```

### Step 5: Run the Application

In your browser, go to:

```
http://localhost/onlline-survey-system-using-xampp/
```

The login page should appear.

---

## 🚀 Usage

- Log in as an **admin** to create and manage surveys.
- Log in as a **user** to answer available surveys.
- Navigate based on your user role to access relevant pages.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add YourFeature"
   ```
4. Push to your branch  
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request

---

## License

Distributed under the MIT License. See [LICENSE](https://github.com/Dixon1323/smart-hydrophonics-system/blob/main/LICENSE.md) for more information.

---

## 🙏 Acknowledgements

A big thanks to the open-source community and online platforms that helped me during this project:

- [YouTube](https://www.youtube.com/)
- [GitHub](https://github.com/)
- [Stack Overflow](https://stackoverflow.com/)
