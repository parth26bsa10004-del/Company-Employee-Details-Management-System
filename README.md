# Company-Employee-Details-Management-System
This terminal-based Python Employee Management System provides a clean CLI for core HR tasks. It supports full CRUD operations—adding profiles, viewing tabbed rosters, searching by ID, updating salaries, and deleting entries. It also identifies top earners and filters by department, using robust exception handling to prevent crashes.

# 🏢 Employee Management System (EMS)

A lightweight, terminal-based **Employee Management System** built with pure Python. It provides an intuitive Command-Line Interface (CLI) for performing essential HR workflows, managing employee records in real time, and querying key workforce insights.

---

## 📌 Features

- **➕ Add Employee:** Register new employees with ID, Name, Department, and Salary.
- **📋 Display All Records:** Render a clean, tab-formatted table of all registered employees.
- **🔍 Search by ID:** Instant lookup for employee details using their unique ID.
- **✏️ Update Salary:** Dynamically locate employees and adjust salary records.
- **🗑️ Delete Employee:** Safely remove employee profiles from the system.
- **⭐ Priority Employee (Top Earners):** Automatically detect and aggregate the highest-paid employee(s) (handles ties seamlessly).
- **🏢 Search by Department:** Perform case-insensitive filters to list employees by department (e.g., `HR`, `Engineering`, `Sales`).
- **🛡️ Input Validation:** Built-in error handling prevents application crashes from invalid numeric entries.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your machine. No external dependencies or packages required!

### Execution

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/employee-management-system.git](https://github.com/your-username/employee-management-system.git)
   cd employee-management-system

2. **Run the application**
     python main.py

🛠️ Tech Stack & Concepts Used
Language: Python 3

Data Structure: In-memory 2D Lists (List of Lists)

3. **Key Concepts**
try...except Exception Handling
List Comprehensions & Generator Expressions
for...else Control Structures
Case-Insensitive String Normalization (.strip(), .lower())
Linear Search & Dynamic Filtering

📝 License
Distributed under the MIT License. See LICENSE for more information.

**Output**
--- EMPLOYEE MANAGEMENT SYSTEM ---
1. Add Employee
2. Display All Employees
3. Search Employee by ID
4. Update Salary
5. Delete Employee
6. Priority Employee (Top Earners)
7. Search by Department
8. Exit

Select option (1-8): 1
ID: E101
Name: John Doe
Department: Engineering
Salary: 75000
Saved record...
