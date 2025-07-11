

---

```markdown
# 📚 Full Stack Book Management System (Angular + Spring Boot + JWT)

A secure and user-friendly full stack web application for managing books, built with **Angular** for the frontend and **Spring Boot** for the backend. The system features **JWT-based authentication**, full **CRUD operations**, and interactive **Swagger API documentation**.

---

## 🔥 Features

### 🧑‍💻 User Features
- ✅ User registration & login
- 🔐 Secure session using JWT tokens
- 📖 View all available books
- 📘 View book details by ISBN

### 📘 Admin Features
- ➕ Add a new book
- 🔁 Update book information
- ❌ Delete a book
- 🔍 Search books

---

## 🧰 Tech Stack

### 🔧 Backend (Spring Boot)
- Java 17
- Spring Boot 3
- Spring Security (JWT)
- Spring Data JPA
- Hibernate
- MySQL
- Swagger (Springdoc OpenAPI)

### 💻 Frontend (Angular)
- Angular 16+
- Angular Routing & Modules
- Angular Reactive Forms
- Bootstrap 5 (UI Styling)
- HTTP Client Module
- JWT Interceptor and Auth Guard

---

## 🧱 Folder Structure

### Backend: `spring-boot-backend`
```

com.example.demo
├── config            # Security & JWT configuration
├── controller        # REST API endpoints
├── model             # Entity classes (e.g., Book, User)
├── repository        # JPA repositories
├── service           # Business logic
├── exception         # Global exception handling
└── dto               # DTO classes for payloads

```

### Frontend: `angular-frontend`
```

src/
├── app/
│   ├── components/          # Book list, book form, navbar, login/register
│   ├── services/            # Book & Auth services
│   ├── models/              # Book & User interfaces
│   ├── guards/              # Auth Guard
│   └── interceptors/        # JWT Interceptor

````

---

## 🚀 How to Run

### ⚙️ Backend Setup (Spring Boot)

1. Clone the backend repo:
   ```bash
   git clone https://github.com/your-username/book-management-backend.git
   cd book-management-backend
````

2. Configure MySQL in `application.properties`:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/bookdb
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```

3. Run the application:

   ```bash
   mvn spring-boot:run
   ```

4. Access Swagger UI:

   ```
   http://localhost:9956/swagger-ui/index.html
   ```

---

### 🌐 Frontend Setup (Angular)

1. Clone the frontend repo:

   ```bash
   git clone https://github.com/your-username/book-management-frontend.git
   cd book-management-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the frontend:

   ```bash
   ng serve
   ```

4. Visit:

   ```
   http://localhost:4200
   ```

---

## 🔐 Authentication Flow

1. **Register/Login** using the Angular frontend.
2. JWT token is stored in local storage.
3. All subsequent HTTP requests include the JWT token in headers.
4. Auth Guard ensures only authenticated users can access protected routes.


---

## ✅ Postman Collection & Swagger

* Swagger UI:
  [http://localhost:9956/swagger-ui/index.html](http://localhost:9956/swagger-ui/index.html)

* Postman Collection:
  Add if available

---

## 👨‍💻 Author

**Udhaya Moorthy**
💼 Spring Boot | Angular | JWT | REST APIs
📢 [Google Slides - Project PPT](https://docs.google.com/presentation/d/1VN3f1qFk0-0HZxgx_cwZ3Tvcz-QOLvEa/edit?usp=sharing&ouid=101941230146649101203&rtpof=true&sd=true)



---

Would you like this README in a `.md` file or `.docx` format for download?
```
