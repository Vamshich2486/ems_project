
# Employee Management System (EMS)

A simple web-based Employee Management System built using Spring Boot, Thymeleaf, and Bootstrap. This application allows administrators to manage employee data — including adding, editing, viewing, and deleting employees — through a clean and intuitive UI.


 📂 Project Structure
ems_project/
│
├── src/
│ ├── main/
│ │ ├── java/com/example/ems/ # Java source files
│ │ ├── resources/
│ │ │ ├── static/ # CSS and static files
│ │ │ │ └── style.css
│ │ │ ├── templates/ # HTML templates (Thymeleaf)
│ │ │ │ ├── login.html
│ │ │ │ ├── dashboard.html
│ │ │ │ ├── employees.html
│ │ │ │ └── add_employee.html
│ │ │ └── application.properties
│ └── test/...
│
├── pom.xml # Maven config
└── README.md




## ⚙ Functionalities

🔑 Secure Admin Authentication
📈 Dashboard with Employee Summary
👥 Employee List View
➕ Add Employee Records
📝 Modify Employee Details
🗑️ Remove Employee Information

---

 ## How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/ems_project.git
   cd ems_project

mvn spring-boot:run

Username: admin
Password: admin123
