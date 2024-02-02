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

## TODO FullStack Application - Features and APIs
##Features
### Task Management:
Add new tasks with due dates.
Edit existing tasks.
Delete tasks.
Mark tasks as completed.
View tasks with due dates and completion status.

###Task Sorting:

Sort tasks by due date.
Sort tasks by completion status.

### Task Filtering:

Filter tasks based on a date range.
Display only completed tasks.
Display only incompleted tasks.

### User Interface:

Intuitive UI with checkboxes to mark completion.
Options to edit and delete tasks.
Due dates displayed for each task.
Stylish icons for editing and deleting tasks.

##Backend APIs
### Fetch All Tasks:

Endpoint: /api/todos
Method: GET
Description: Retrieve all tasks from the database.

- Add New Task:

Endpoint: /api/todos
Method: POST
Description: Add a new task to the database.

- Delete Task:

Endpoint: /api/todos/{id}
Method: DELETE
Description: Delete a task based on its ID.

- Update Task:

Endpoint: /api/todos/{id}
Method: PUT
Description: Update an existing task based on its ID.

- Complete Task:

Endpoint: /api/todos/{id}/complete
Method: PUT
Description: Mark a task as completed based on its ID.

## Frontend Implementation
Task Component (Todo.jsx):

- Displays task details, including task name, due date, and completion status.
Provides checkboxes to mark tasks as completed.
Icons for editing and deleting tasks.
Task Form Component (TodoForm.jsx):

- Allows users to input new task details.
Supports due date input for tasks.
Edit Task Form Component (EditTodoForm.jsx):

- Provides a form for editing existing tasks.
Task Wrapper Component (TodoWrapper.jsx):

- Fetches tasks from the backend on component mount.
Manages state for tasks, due date filters, and sorting preferences.
Utilizes react-datepicker for date range selection.
Communication with Backend (axios):

- Uses Axios for making HTTP requests to the backend.
Implements CRUD operations for tasks.
Styling (CSS):

 - Styled components for an aesthetically pleasing UI.
Custom styling for checkboxes, icons, and forms.

##Additional Points
- Database Connection (application.yml):

- Configured the PostgreSQL database connection details in the Spring Boot application configuration.
- Maven Build (mvn clean install):

- Configured Maven for building and packaging the Spring Boot application.
- SDK Version (Java 21):

- Set the Java SDK version to 21 in the IntelliJ project.
- Git Repository Setup (git remote add origin):

- Configured Git remote for pushing changes to the GitHub repository.
- By implementing these features and APIs, the TODO FullStack Application provides a user-friendly task management system with sorting, filtering, and editing capabilities.

