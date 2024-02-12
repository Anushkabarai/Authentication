# This project is a simple Java web application built using JSP (JavaServer Pages) and Servlets. The purpose of this project is to demonstrate user authentication functionality using predefined data stored in MySQL. Users can log in by providing their username and password, and upon successful authentication, they will be granted access to the system.

# Setup Instructions
1.Clone the Repository:
 Clone this repository to your local machine using Git:
 git clone https://github.com/Anushkabarai/authentication
 
2.Database Setup:
 Make sure you have MySQL installed on your system.
 Create a MySQL database and import the provided schema (database.sql) to create the necessary tables and data.
 
3.Configure Database Connection:

 Open the src/main/java/com/example/util/DBUtil.java file.
 Modify the database connection parameters (DB_URL, DB_USER, DB_PASSWORD) to match your MySQL configuration.
 
4.Deploy the Application:
 Deploy the project to a Servlet container like Apache Tomcat. You can copy the WAR file to the webapps directory of Tomcat or deploy it using Tomcat's manager application.

5.Accessing the Application:
 Once deployed, access the application through a web browser using the URL provided by your Servlet container (e.g., http://localhost:8080/your-app).

#Usage
 Upon accessing the application, you will be presented with a login page.
 Enter your username and password.
 Click the "Login" button.
 If the provided credentials match the ones stored in the database, you will be logged in and redirected to the home page.
 If the credentials are incorrect, an error message will be displayed, and you can try again.

#Project Structure
 src/main/java/com/example/servlets: Contains Servlet classes responsible for handling requests.
 src/main/java/com/example/util: Utility classes, such as database connection (DBUtil).
 src/main/webapp: Contains JSP files and static resources (CSS, JavaScript).
 database.sql: SQL script for creating the database schema and sample data.

#Technologies Used
 Java Servlets
 JSP (JavaServer Pages)
 MySQL
