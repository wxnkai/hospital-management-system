# 🏥 Hospital Management System

**⚠️ Archived Project**

This repository is archived and no longer actively maintained. It was developed as a university assignment for a **Java Object-Oriented Programming (OOP)** course.

## Overview

The **Hospital Management System (HMS)** is a comprehensive desktop application designed to streamline and automate the core operations of a hospital. Built with **Java** and **JavaFX**, it provides an intuitive graphical user interface (GUI) to manage doctors, patients, medical supplies, staff, laboratories, and facilities，all backed by a relational database via JDBC.

## Features

- 👨‍⚕️ **Doctor Management** — Add, view, and manage doctor records and specialisations
- 🧑‍🤝‍🧑 **Patient Records** — Register and track patient information and history
- 💊 **Medical Supplies** — Monitor inventory of medicines and hospital supplies
- 👩‍💼 **Staff Information** — Manage hospital staff details and roles
- 🔬 **Laboratory** — Record and retrieve lab test information
- 🏢 **Facilities** — Track hospital facilities and resource allocation
- 🖥️ **GUI Interface** — Clean and user-friendly JavaFX interface for all operations

## Tech Stack

| Component | Technology |
|---|---|
| Language | Java |
| UI Framework | JavaFX |
| Database | SQL (via JDBC) |
| Build | Manual / VS Code Java Extension |

## Folder Structure

```
hospital-management-system/
├── src/        # Java source files
└── lib/        # External dependencies
```

## Prerequisites

- **Java JDK** 11 or higher
- **JavaFX SDK** — Download from [https://openjfx.io/](https://openjfx.io/)
- A compatible SQL database (e.g., MySQL, SQLite)

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/wxnkai/hospital-management-system.git
   cd hospital-management-system
   ```

2. **Set up JavaFX**
   Download the JavaFX SDK from [openjfx.io](https://openjfx.io/) and configure the `lib/` path in your IDE or build script.

3. **Configure the database**
   Update the JDBC connection string in the source with your database credentials and run the provided SQL schema to initialise the tables.

4. **Run the application**
   ```bash
   java --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml -cp src Main
   ```

## Screenshots

**Main Menu**

![Main Menu](https://github.com/wthislifehuh/HospitalManagementSystem/blob/main/src/resources/Main_Menu.jpg?raw=true)

**Add Information**

![Add Info](https://github.com/wthislifehuh/HospitalManagementSystem/blob/main/src/resources/Add_Info.jpg?raw=true)

## Academic Context

This project was developed as part of a **Java Object-Oriented Programming (OOP)** university course assignment. It demonstrates the application of core OOP principles including encapsulation, inheritance, polymorphism, and abstraction in the context of a real-world system.

> This repository is **archived** — no pull requests or issues will be reviewed.

## License

This project is for educational purposes only. All rights reserved by the authors.
