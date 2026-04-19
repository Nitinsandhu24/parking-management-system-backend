# parking-management-system-backend
This project is a backend system built using Spring Boot to manage parking operations efficiently. It provides APIs for user management, parking slot booking, and analytics. The system is designed to be scalable and modular.

Tech Stack
1.Java
2.Spring Boot
3.Spring Security
4.Hibernate (JPA)
5.MySQL
6.Maven

Setup 
1.git clone https://github.com/Nitinsandhu24/parking-management-system-backend
2.cd parking-management-system-backend
3.spring.datasource.url=jdbc:mysql://localhost:3306/your_database 
  spring.datasource.username=root 
  spring.datasource.password=your_password 
  spring.jpa.hibernate.ddl-auto=update 
  spring.jpa.show-sql=true
4.mvn spring-boot:run

the server will start port 8080



few Api you can test
Auth APIs :
1. POST /api/auth/signup → Register new user
2. POST /api/auth/login → Login user
User APIs :
1. GET /api/users → Get all users
Analytics APIs :
1. GET /api/analytics/dashboard → Get dashboard data
