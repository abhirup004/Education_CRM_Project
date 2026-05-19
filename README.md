# Education CRM Project

A comprehensive Customer Relationship Management (CRM) system tailored for educational institutions, built with Spring Boot, Thymeleaf, and MySQL. It features inquiry management, course purchasing, follow-ups tracking, and Razorpay integration for seamless payment processing.

## Technologies Used
- **Backend:** Java 17, Spring Boot 3.3.1, Spring Data JPA, Hibernate
- **Frontend:** Thymeleaf (HTML, CSS)
- **Database:** MySQL
- **Payment Gateway:** Razorpay API Integration
- **Build Tool:** Maven

## Setup Instructions

### 1. Database Configuration
Ensure MySQL is installed and running. Create a database named `education_crm_db`:
```sql
CREATE DATABASE education_crm_db;
```

Update the `src/main/resources/application.properties` file with your MySQL credentials if necessary:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/education_crm_db
spring.datasource.username=root
spring.datasource.password=NewPassword123!
```

### 2. Running the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/abhirup004/Education_CRM_project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd "Education_CRM_project "
   ```
3. Build and run the Spring Boot application using Maven:
   ```bash
   ./mvnw spring-boot:run
   ```
4. Access the application in your web browser (default port usually `8080`).

## Key Features
- **Inquiry Management:** Keep track of prospective students and their inquiries.
- **Follow-ups Tracking:** Schedule and manage follow-up communications effectively.
- **Course Purchasing:** Integrated Razorpay checkout for secure course purchases.
- **Admin Management:** Centralized management capabilities through the Admin controller.

## License
This project is for educational and portfolio purposes.
