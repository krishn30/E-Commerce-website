# 🛒 E-Commerce Website (Spring Boot)

This project is a **Spring Boot-based E-commerce website** that allows users to browse products, manage a shopping cart, and place orders, while admins can manage users and products.  
It provides secure authentication, role-based access, and database integration.

---

📌 **Features**
- Browse products in the catalog  
- User authentication (Admin / Customer roles)  
- Add to cart and checkout  
- View order history  
- Admin panel for managing products & users  
- Secure login with BCrypt password encryption  
- RESTful APIs for frontend integration  

---

🧠 **Technologies Used**
- Java (Spring Boot, Spring Security, Spring Data JPA)  
- MySQL Database  
- Hibernate ORM  
- Maven (Build tool)  
- Thymeleaf (for server-side rendering, optional React/Angular for frontend)  

---

🎯 **How It Works**
- Captures user requests via **Spring MVC Controllers**  
- Manages product and user data using **Spring Data JPA + MySQL**  
- Customers can **browse, add to cart, and place orders**  
- Admins can **create, update, and delete products/users**  
- Authentication & authorization handled via **Spring Security**  

---

🚀 **Getting Started**

1️⃣ **Clone the repo**

git clone https://github.com/krishn30/E-Commerce-website.git
cd E-Commerce-website

2️⃣ Configure the database
Update src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update

3️⃣ Build & Run
mvn clean install
mvn spring-boot:run

4️⃣ Access the app
Open browser → http://localhost:8080


