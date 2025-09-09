# 📇 Smart Contact Manager

A full-stack **Contact Management Web Application** built with **Spring Boot** and modern web technologies.  
It allows users to securely manage their contacts, send emails, and store contact information with cloud integration.  

---

## 🚀 Features

- 🔐 **User Authentication & Authorization**
  - Signup/Login with Email & Password
  - Email Verification Link
  - Google & GitHub OAuth Login
  - Role-based access with Spring Security

- 👥 **Contact Management**
  - Add, Update, View, and Delete Contacts
  - Upload Contact Picture (stored in AWS/Cloudinary)
  - Mark Favorite Contacts
  - Search and Pagination Support
  - Export Contacts to **Excel/PDF**

- 📧 **Email Integration**
  - Compose and send emails directly from SCM
  - Supports text + attachments

- 👤 **User Profile**
  - Update personal details
  - Dark/Light Theme Support

- 📊 **Other Utilities**
  - Feedback system
  - Responsive UI with TailwindCSS + Flowbite

---

## 🛠️ Tech Stack

**Backend**
- Spring Boot (Latest)
- Spring MVC
- Spring Data JPA (MySQL/PostgreSQL)
- Spring Security
- Java Mail Services
- Validation

**Frontend**
- Thymeleaf Template Engine
- JavaScript
- TailwindCSS + Flowbite Components

**Cloud & Tools**
- AWS / Cloudinary SDK (file storage)
- OAuth (Google, GitHub)
- PDF/Excel generation tools
- Git, Postman, Docker (optional)

---

## 📂 Project Structure

```plaintext
Smart-Contact-Manager/
 ┣ 📁 src/main/java/com/scm   # Backend code
 ┣ 📁 src/main/resources      # Templates, static files, application configs
 ┣ 📁 static/                 # CSS, JS, assets
 ┣ 📁 templates/              # Thymeleaf templates
 ┣ 📄 pom.xml / build.gradle  # Dependencies
 ┣ 📄 README.md               # Documentation
