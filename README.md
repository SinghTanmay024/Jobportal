# Job Portal - Full Stack Spring Boot Application

## Description
This is a full-stack web application built using **Spring Boot**, **Thymeleaf**, and **MySQL**. The project implements a job portal where users can register, log in, and search for jobs.

## Technologies Used
- **Backend:** Spring Boot
- **Frontend:** Thymeleaf, Bootstrap, jQuery
- **Database:** MySQL
- **Security:** Spring Security


## Installation and Setup
Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/job-portal.git
   cd job-portal
   ```

2. **Create a MySQL database**
   Open your MySQL client and run:
   ```sql
   CREATE DATABASE jobportal;
   ```

3. **Update `application.properties` file**
   Navigate to `src/main/resources/application.properties` and update the database credentials:
   ```properties
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   spring.datasource.url=jdbc:mysql://localhost:3306/jobportal
   spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
   
   spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect
   ```

4. **Build and Run the application**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

5. **Access the application**
   Open your browser and visit:
   ```
   http://localhost:8080
   ```

## Features
- User authentication (registration & login)
- Role-based access control
- Job listing and search
- Responsive UI with Bootstrap

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is licensed under the MIT License.

