## Project Documentation
This documentation provides a step-by-step guide on running the TODO FullStack Application locally. 
The application consists of a frontend built with HTML, CSS, and React.js, and a backend developed with Java Spring Boot, 
using PostgreSQL as the database.

## Technologies Used
 ## Frontend:
HTML
CSS
JavaScript
React.js

 ## Backend:
Java Spring Boot

## Database:
PostgreSQL

## Running the Frontend
Navigate to the todolist-frontend directory.

### `cd todolist-frontend`
Install dependencies using npm.

### `npm install`
Start the development server.

### `npm start`
The frontend will run on http://localhost:3000.

## Running the Backend
-Open the todolist-backend directory in IntelliJ or your preferred Java IDE.

 ##Configure the PostgreSQL Database:

-Open src/main/resources/application.yml.
-Replace the spring.datasource.username and spring.datasource.password with your PostgreSQL credentials.
-Specify the desired database name in spring.datasource.url.
-Set the SDK version to 21 in IntelliJ.

## Build the project using Maven. Run the following command in the terminal.

### `mvn clean install`
- Run the Spring Boot application.

- The backend will be accessible at http://localhost:8081.

## Additional Notes
-Ensure that PostgreSQL and mypgadmin4 are installed on your system.

-Start the PostgreSQL server using mypgadmin4 and note the username and password used during installation.

-Follow these steps, and you should have the TODO FullStack Application up and running on your local machine.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


