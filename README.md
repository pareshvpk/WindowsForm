# WindowsForm
A C# Windows Forms application with full CRUD operations using SQL Server. Supports Insert, View, Update, Delete directly through a DataGridView with automatic database synchronization. Built for learning backend fundamentals with C#.

# Windows Forms CRUD Application (C# + SQL Server)

A complete Windows Forms application built using **C#** and **SQL Server**, demonstrating all essential **CRUD** operations:

- **Insert** new records
- **View** all records in a DataGridView
- **Edit/Update** directly inside the table
- **Delete** selected rows
- **Automatic database update using SqlDataAdapter + SqlCommandBuilder**

This project is built for learning backend fundamentals in C# and understanding how Windows Forms interacts with SQL Server using ADO.NET.

---

## 🚀 Features

### ✔ Insert Page
- Accepts Name, Age, Mobile, Mail
- Validates input
- Automatically generates and returns inserted ID
- Uses `ExecuteScalar()` with `OUTPUT INSERTED.ID`

### ✔ View Page (Direct Table Editing)
- Displays full SQL table inside DataGridView
- Edit rows directly (like Excel)
- Save changes using Update button
- Delete row using Delete button
- Primary Key (ID) is read-only

### ✔ Backend Logic
- Uses `SqlConnection`, `SqlCommand`, `SqlDataAdapter`, `DataTable`
- `SqlCommandBuilder` automatically generates INSERT/UPDATE/DELETE SQL
- Fully synchronized frontend ⇄ backend

---

## 🛠 Technologies Used

- **C# (Windows Forms)**
- **.NET Framework / .NET**
- **ADO.NET**
- **SQL Server**
- **DataGridView**
- **Visual Studio**

---

## 🗂 Project Structure
├── Form1.cs # Insert Form
├── Data.cs # View+Update+Delete Form
├── App.config
├── Program.cs
└── README.md
