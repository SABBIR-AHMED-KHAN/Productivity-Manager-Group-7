# Productivity-Manager-Group-7
This Java project is done for GUVI. Group - 7, Section - 42, Galgotias University.
# Productivity Manager

**Productivity Manager** is a Java console-based application designed to help users manage and prioritize their daily tasks. It allows adding, viewing, validating, and saving tasks with an emphasis on productivity.

---

## 🚀 Features

- ✅ Add new tasks with descriptions and priorities
- 📋 View all existing tasks
- 🧹 Validate task input (e.g., description length, date format)
- 💾 Save and load tasks from a local file (`tasks.txt`)
- 🧩 Modular structure with clear separation between data access, UI, logic, and utilities

---

## 🛠 Technologies Used

- Java (Standard Edition)
- IntelliJ IDEA (Project structure with `.iml` and `.idea/`)
- File I/O for task persistence
- Object-oriented design with DAO pattern

---

## 📁 Folder Structure

```
Productivity Manager/
├── src/
│   └── com/productivitymanager/
│       ├── dao/           # Data Access Objects (TaskDAO, TaskFileDAO)
│       ├── model/         # Task models (Task, PriorityTask)
│       ├── ui/            # Console UI handling
│       ├── utils/         # Validation and formatting
│       └── main/          # Main application entry point
├── tasks.txt              # Stored tasks
├── .idea/, *.iml          # IntelliJ IDEA config files
```

---

## 🧪 How to Run

1. **Open in IntelliJ IDEA**:
   - File > Open > Select `Productivity Manager` directory

2. **Build and Run**:
   - Run `MainApp.java` from `com.productivitymanager.main`

3. **Use the Console Menu** to:
   - Add new tasks
   - View existing tasks
   - Exit the application

> 📝 Tasks are automatically loaded from and saved to `tasks.txt`

---

## 📄 License

This project is for educational project purposes - for GUVI.

---

## 👤 Author

Admin: Sabbir Ahmed Khan
Member: Mithun Chandra Roy, Mrittic Roy, Sushmita Gosh
