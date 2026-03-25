🚗 Vehicle Inventory Management System

A full-stack **Vehicle Inventory Management System** built using **Spring Boot**, focusing primarily on backend development with a minimal frontend using Thymeleaf.

🔗 Live Demo
https://vehicle-inventory-production.up.railway.app/vehicles

📌 Features

* ➕ Add new vehicles to inventory
* 📋 View all vehicles
* ✏️ Update vehicle details
* ❌ Delete vehicles
* 🔍 Search and manage inventory efficiently
* 🌐 Deployed on cloud (Railway)

🛠️ Tech Stack
Backend:
* Java
* Spring Boot
* Spring Data JPA
* Hibernate
  
Frontend:
* Thymeleaf
* HTML / CSS

Database:
* MySQL (Railway Cloud Database)

⚙️ Configuration

Environment variables used for secure deployment:

```properties
spring.datasource.url=jdbc:mysql://${MYSQLHOST}:${MYSQLPORT}/${MYSQLDATABASE}
spring.datasource.username=${MYSQLUSER}
spring.datasource.password=${MYSQLPASSWORD}
server.port=${PORT:8080}
```


🚀 Deployment
* Hosted on Railway
* Connected to MySQL cloud database
* Uses environment variables for secure configuration

  
🧠 Learning Highlights

* Implemented CRUD operations using Spring Boot
* Connected application to cloud-hosted MySQL database
* Managed environment variables for secure deployment
* Deployed full application on cloud platform


📬 Contact

Feel free to connect with me for any queries or collaboration!

⭐ If you like this project, don’t forget to star the repository!
