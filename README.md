Spring Boot Day 1 Exercise
Exercise Title: Set Up a Spring Boot Project with MySQL Integration
Objective:
You are a backend developer setting up the foundational project structure for a new employee
management system. Your goal today is to:
- Create a Spring Boot project with Maven
- Connect it to a MySQL database
- Ensure that the connection is properly logged and ready for future CRUD operations
Requirements:
1. Create a new Spring Boot application using Maven.
2. Use MySQL as the database.
3. Project Structure should include:
- controller/
- service/
- repository/
- model/
4. Configure the application.properties to connect to:
- Database: employee_db
- Username: root
- Password: your_password
- Add the correct JDBC URL
5. Include these dependencies in your pom.xml:
- spring-boot-starter-web
- spring-boot-starter-data-jpa
- mysql-connector-j
- lombok
6. Create a simple DemoApplication.java file and verify that:
- Application starts
- Database connection log appears correctly
- No startup errors
Bonus Task (Optional):
Add a simple @PostConstruct method inside the main class that prints a confirmation message:
@PostConstruct
public void init() {
System.out.println("Spring Boot project initialized with MySQL");
}
Submission Checklist:
- Project compiles without error
- application.properties connects to MySQL
- Database logs show successful startup
- Project has the correct folder structure
Time Allocation:
Task | Time
--------------------------|------
Project Setup | 1 hr
MySQL Configuration | 1 hr
Writing Properties File | 30 mins
Testing & Debugging | 1 hr
Hands-on Practice | 2 hrs
Q&A / Wrap-up | 30 mins
