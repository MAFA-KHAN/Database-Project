# 🏢 Prime Tech Management System (PTMS)

<div align="center">

![Project Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=for-the-badge)
![Framework](https://img.shields.io/badge/.NET-WPF-512BD4?style=for-the-badge\&logo=dotnet)
![Database](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge\&logo=mysql)
![Language Support](https://img.shields.io/badge/Languages-English-FF6B6B?style=for-the-badge)

*A professional-grade business management desktop system for overseeing export operations between Pakistan and Iran, developed exclusively for Prime Tech.*

</div>

---

## 🖼️ System Screenshots

> *Below are key interface visuals from PTMS. These demonstrate the professionalism, usability, and WPF interface design of the system.*

```md
<!-- Replace these placeholder paths with your actual screenshot file paths -->

![Welcome Screen](./assets/welcome.png)
*Elegant Welcome Screen — Designed for a smooth onboarding experience*

![Sign Up Page](./assets/signup.png)
*User Registration with Field Validation & Responsive Styling*

![Sign In Page](./assets/signin.png)
*Secure Sign-In with Role-Based Access Handling*

![README Dashboard](./assets/dashboard.png)
*Main Dashboard - Overview of supplier activities and metrics*
```

---

## 🎯 Overview

**PTMS (Prime Tech Management System)** is a WPF-based desktop application tailored to manage and streamline export logistics for Prime Tech — a company exporting premium mangoes from Pakistan to Iran. The system empowers the business owner (Admin), certified suppliers, and a reporting employee to efficiently coordinate the export supply chain, generate insightful reports, and maintain secure records.

### 🚀 Key Objectives

* **Centralize Export Operations** — Manage all supplier activity and shipment status in one place
* **Streamline Communication** — Role-based access and responsibilities for admin, suppliers, and employees
* **Monitor Supplier Performance** — Generate automated PDF reports based on supplier ratings
* **Secure Data Handling** — Role-based login with email verification
* **Real-time Reporting** — Day-to-day export tracking and activity logs

---

## ✨ Key Features

* 🔐 Role-based Authentication (Admin / Supplier / Employee)
* 🧑‍💼 Supplier Database Management
* 📦 Export Tracking & Records
* 📝 Automated Report Generation (PDF)
* 📈 Supplier Performance Ratings
* 📬 Email Verification via SMTP (Gmail)
* 📊 Visual Dashboards with LiveCharts
* 🌐 English Language Support

---

## 🏗️ System Architecture

```mermaid
graph TD
    UI["WPF Frontend (XAML)"] --> Logic["C# Code-Behind"]
    Logic --> DB["MySQL Database"]
    Logic --> PDFGen["QuestPDF for Report Generation"]
    Logic --> Charting["LiveCharts.WPF"]
    Logic --> Mail["SMTP (Gmail) Integration"]
    UI --> Auth["Login, Signup Pages"]
    Logic --> SupplierMgmt["Supplier Data CRUD"]
    Logic --> Reports["PDF & Excel Reports"]
    Reports --> Output["Printable Reports"]
```

---

## 🔧 Technology Stack

* **Frontend:** WPF (.NET, XAML)
* **Backend:** C# (.NET Framework)
* **Database:** MySQL
* **Authentication:** SMTP with Gmail
* **Reporting:** QuestPDF (PDF), basic CSV support
* **Charts:** LiveCharts.WPF
* **Packages Used:**

  * `MySql.Data`
  * `QuestPDF`
  * `LiveCharts.Wpf`
  * `System.Net.Mail`

---

## 👥 User Roles

### 🧑‍💼 Admin (Owner)

* View supplier performance
* Track shipment reports
* Oversee full system activity

### 🚛 Supplier

* Add and manage export product details
* Handle logistics and delivery to Iran
* Manage customer information and ratings
* Monitor shipment status and feedback

### 📊 Employee

* Enter/export shipment data
* Generate and export reports
* Rate suppliers day-wise

---

## 📈 Reporting & Analytics

* 📄 Daily Reports on Shipment Volume
* ⭐ Supplier Rating Reports
* 🧾 Printable PDF Exports
* 📊 Graphical Analysis using LiveCharts

---

## 🔒 Security Features

* Role-based Authentication
* Secure login system (email + password)
* SMTP Verification for email
* Encrypted storage (MySQL)

---


## 📌 Credits

Built with ❤️ for Prime Tech as part of an academic final project.

> This project is for **educational use only** and not affiliated with any commercial deployment.

---



</div>
