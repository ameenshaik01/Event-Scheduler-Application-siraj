# Event-Scheduler-Application
This is a Spring Boot application that provides a REST API for scheduling events. The API is secured using JSON Web Tokens (JWT). Swagger UI is also provided for easy testing and documentation of the API.

# Features
- User Registration & Login
- Update & Fetch User Details
- Schedule, Update, Delete Event
- Get Event By Type [Day, Week, Month]

# Security
- The API is secured using JSON Web Tokens (JWT). To access the API, you will need to obtain a JWT by authenticating with the /login endpoint. The JWT should then be passed in the Authorize option available in the Swagger-ui.

  ### Example:
  - Authorization: <your_jwt>

# Technologies:
- Java
- Spring Boot 3.0
- Spring Data JPA
- JSON Web Tokens (JWT)
- MySQL
- Swagger-ui

# Running the app
1. Clone the repository: git clone https://github.com/Sirajuddin135/Event-Scheduler-Application.git
2. Import the project into STS:
  - Click File > Import...
  - Select Maven > Existing Maven Projects and click Next
  - Browse to the project directory and click Finish
3. Update the values in application.properties with your MySQL database connection details.
4. Run the app: Right-click the project in the Package Explorer and click Run As > Spring Boot App.
5. The app will be running at http://localhost:8080.

# API documentation
- API documentation is available via Swagger UI at http://localhost:8080/swagger-ui.html.

# ER-Diagram
![ER_Diagram](https://user-images.githubusercontent.com/101395494/210177816-c40d34a0-ebb9-488d-b904-35ccf4ad417c.jpg)

# Swagger-ui
<img width="948" alt="Swagger-ui" src="https://user-images.githubusercontent.com/101395494/210170660-4f6bd3b0-ec1b-411f-82c1-c059ad14d567.png">

# API Controllers
<img width="939" alt="Event App Controllers" src="https://user-images.githubusercontent.com/101395494/210179001-2b271f7a-6f13-4060-979b-e88e5a803a93.png">

# Thank You