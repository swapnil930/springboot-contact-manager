# Contact Management Application

This is a full-stack web application for managing contacts, built with **ReactJS** on the frontend and **Spring Boot** on the backend. It allows users to create, view, update, and delete contacts. The app is designed to be fast, responsive, and user-friendly.

## Features

### Frontend
- Built using **ReactJS** with a modern, component-based architecture.
- Interactive UI with live updates for adding, viewing, and editing contacts.
- **Bootstrap** integration for an elegant, responsive design.
- Error handling and loading states with spinners for a smooth user experience.

### Backend
- Powered by **Spring Boot**, with a scalable and efficient REST API.
- **JPA/Hibernate** is used for database management.
- Well-structured CRUD operations with proper HTTP status responses.

## Technologies Used

- **ReactJS** for building the user interface.
- **Axios** for HTTP requests.
- **React Router** for page navigation.
- **Spring Boot** for backend services.
- **JPA/Hibernate** for database management.
- **MySQL** as the database for storing contacts.

## Setup and Installation

### Backend (Spring Boot)

1. Clone the repository:
- Clone the repository: You clone the Spring Boot project from GitHub to your local machine (download zip file and extract it in your system).
- Setup spring tool: Download spring tool and extract it. launch it.
  
```bash
https://spring.io/tools
```
- Open the project: Once download all, open the project folder in an IDE like SpringToolSuite4 for eclips.  
- OR
- Create project: Create new Spring starter project in spring tool.
- Select defendancy:
   1. From SQL section choose 'MYSQL' and 'Spring data'.
   2. From web section choose 'Spring Web'.
   3. From devloper tool section 'Sringboot dev tool' and 'Lambok'.
   4. click 'Next'.
   5. Configure database connection inside Application.Properties (refer code).
   6. Add pakages and create class (follow github files code refernce for creating project structure).
- Run application or server: Inside base package there is class ContactManagerApplication Run that class.
- Now your springboot server will ON.

### Frontend (ReactJS)
  1. Open vsCode terminal (Use Following Commands)
  2. Create new react Application : npx create-react-app ContactManagerFrontend
  3. Install bootstrap : npm install bootstrap
  4. Install fontAwesome: npm i @fortawesome/fontawesome-free
  5. Connect fontawesome with html page:	Visit fontawesome (fortawesome/fontawesome-free) official website copy the cdn link and paste in index.html.
  6. Install Axios: npm i axios
  7. Install React-Router: npm install react-router-dom@6
- All defendancy setup done....
- Now inside src file create folder structure (refer ContactManagerFrontend file).
