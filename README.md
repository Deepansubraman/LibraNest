# 📚 LibraNest – Online Bookstore Management System

### 🧑‍💻 Role: Developer  
**Tech Stack:** Java | Spring Boot | MySQL | HTML | CSS | JavaScript

---

## 📖 Overview
**LibraNest** is a full-stack **Online Bookstore Management System** that allows users to efficiently manage book inventories.  
The system provides complete **CRUD (Create, Read, Update, Delete)** functionality for books using **RESTful APIs** built with **Spring Boot** and a **MySQL** database.  
The frontend, developed using HTML, CSS, and JavaScript, communicates with the backend using **fetch API** calls, ensuring a seamless and responsive user experience.

---

## 🚀 Features
- 📗 Add, update, delete, and view book records  
- ⚙️ REST API-based backend built with Spring Boot  
- 🗄️ MySQL integration for data persistence  
- 🌐 Interactive frontend using HTML, CSS, and JavaScript  
- 🔄 Real-time communication between frontend and backend via fetch API  
- 🧾 Organized project structure for easy maintenance and scalability  

---

## 🧩 Project Architecture
```
Frontend (HTML, CSS, JavaScript)
        ↓ (fetch API calls)
Backend (Spring Boot REST APIs)
        ↓
Database (MySQL)
```

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/LibraNest.git
cd LibraNest
```

### 2️⃣ Backend Setup (Spring Boot)
1. Open the project in your preferred IDE (IntelliJ IDEA / Eclipse / VS Code).  
2. Configure **application.properties** with your MySQL database credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/libranest
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
server.port=8080
```

3. Build and run the Spring Boot application.

### 3️⃣ Frontend Setup
1. Navigate to the `frontend` directory (if separated) or open the `index.html` file directly in your browser.  
2. Make sure your backend is running on port `8080`.  
3. The frontend will automatically communicate with the backend via **fetch API** calls.

---

## 🧠 API Endpoints

| Method | Endpoint             | Description        |
|--------|----------------------|--------------------|
| GET    | `/api/books`         | Get all books      |
| GET    | `/api/books/{id}`    | Get book by ID     |
| POST   | `/api/books`         | Add a new book     |
| PUT    | `/api/books/{id}`    | Update a book      |
| DELETE | `/api/books/{id}`    | Delete a book      |

---

## 📂 Project Structure
```
LibraNest/
├── backend/
│   ├── src/main/java/com/libranest/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── repository/
│   │   ├── service/
│   │   └── LibraNestApplication.java
│   └── src/main/resources/
│       └── application.properties
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
└── README.md
```

---

## 🖼️ Screenshots
*(Add screenshots here once available)*  

Example structure:
```
/screenshots/
  ├── home.png
  ├── add-book.png
  ├── update-book.png
```

---

## 🌟 Future Enhancements
- 🔐 User authentication and role-based access  
- 🔍 Book search and filter functionality  
- 🛒 Shopping cart and order management  
- 💳 Payment gateway integration  
- 📦 Docker setup for deployment  

---

## 🤝 Contributing
Contributions are welcome!  
To contribute:
1. **Fork** the repository  
2. Create a new **feature branch** (`feature/your-feature-name`)  
3. **Commit** your changes  
4. **Push** to your fork and submit a **Pull Request**

---

## 🪪 License
This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact
**Developer:** Your Name  
📧 Email: [your.email@example.com](mailto:your.email@example.com)  
🔗 GitHub: [your-username](https://github.com/your-username)  

---

⭐ *If you like this project, please consider starring the repo to support future development!*
