# 🏨 Hotel Management System

This Java application provides a simple Hotel Management System with a graphical user interface for managing guest information.

## ✨ Features

- 📋 View a list of all guests
- ➕ Add new guests
- 🔄 Update existing guest information
- 🗑️ Delete guests from the system

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:

- ☕ Java Development Kit (JDK) 8 or higher
- 🌘 Eclipse IDE
- 🐬 MySQL database server
- 🔌 MySQL Connector/J (JDBC driver for MySQL)

## 📦 Required JAR File

This project uses the following external JAR file:

- `mysql-connector-java-8.0.28.jar` (or the version you're using)

> ⚠️ Make sure to include this JAR file in your project's build path.

## 🗄️ Database Setup

Set up your MySQL database:

1. Create a new database for the Hotel Management System.
2. Create a table named `Guest` to store guest information.
3. Ensure the `Guest` table has appropriate columns for Guest ID, Name, Contact Info, Nationality, Gender, and Reservation History.

## ⚙️ Configuration

Configure your database connection by setting the following environment variables:

- `DB_URL`: Your database URL (e.g., `jdbc:mysql://localhost:3306/your_database_name`)
- `DB_USER`: Your database username
- `DB_PASSWORD`: Your database password

## 🚀 Executing in Eclipse IDE

Follow these steps to run the project in Eclipse:

1. Open Eclipse IDE.
2. Go to `File` > `Import` > `General` > `Existing Projects into Workspace`.
3. Select the root directory of the project and click `Finish`.
4. Right-click on the project in the Package Explorer.
5. Select `Properties` > `Java Build Path` > `Libraries`.
6. Click "Add External JARs" and select the mysql-connector-java JAR file.
7. Apply and close the Properties window.
8. Open the `HotelManagementSystem.java` file.
9. Right-click in the editor and select `Run As` > `Java Application`.

The application should now start, and you'll see the graphical user interface for managing guest information.

## 🖥️ Usage

Use the graphical interface to manage guest information:

- Click "Insert" to add a new guest
- Select a guest and click "Update" to modify their information
- Select a guest and click "Delete" to remove them from the system

## 📜 License

This project is proprietary and not open for contributions or redistribution.

## 📞 Contact

Harsha BR - harshabr39@gmail.com

Project Link: [https://github.com/HarshaBR66/hotelmgmt.git](https://github.com/HarshaBR66/hotelmgmt.git)
