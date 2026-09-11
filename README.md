# E-Learning Platform

A full-stack e-learning platform designed to facilitate online education by connecting students and professors through a modern web application.

The platform provides course management, student enrollment, educational content, quizzes, meeting scheduling, and learning progress tracking.

## Overview

The application is composed of three main components:

* **Frontend:** Angular application providing the user interface.
* **Backend:** Spring Boot application providing REST APIs and business logic.
* **Database:** MySQL for persistent data storage.

The project follows a full-stack architecture where the Angular frontend communicates with the Spring Boot backend through REST APIs.

## Features

### Student

* Register and log in
* Browse available courses
* Subscribe to courses
* Access course content
* Watch educational videos
* Access PDF learning materials
* Take quizzes
* Track learning progress
* Schedule meetings with professors

### Professor

* Create and manage courses
* Manage course content
* Add videos and PDF documents
* Create quizzes
* Manage enrolled students
* Schedule meetings with students
* Monitor student learning progress

### Notifications

* Email notifications for course subscriptions
* Notifications related to course updates and activities

## Technology Stack

| Layer    | Technology  |
| -------- | ----------- |
| Frontend | Angular 16  |
| Backend  | Spring Boot |
| Database | MySQL       |
| API      | REST API    |

## Project Highlights

* Full-stack web application
* Role-based functionality for students and professors
* Course and enrollment management
* Interactive quizzes and learning content
* Learning progress tracking
* Meeting scheduling
* Email notification integration
* Responsive Angular interface

## Project Structure

```text
E-Learning-Platform-Project/
│
├── backend/
│   └── Spring Boot application
│
├── frontend/
│   └── Angular application
│
└── README.md
```

## Getting Started

### Prerequisites

Before running the project, make sure you have installed:

* Node.js
* npm
* Angular CLI
* Java JDK
* Maven
* MySQL
* Git

### Clone the Repository

```bash
git clone https://github.com/sirineelayeb/E-Learning-Platform-Project.git
cd E-Learning-Platform-Project
```

## Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Install the Maven dependencies:

```bash
./mvnw install
```

Start the Spring Boot application:

```bash
./mvnw spring-boot:run
```

> On Windows, use `mvnw.cmd` instead of `./mvnw`.

Make sure MySQL is running and the database configuration in the Spring Boot application is correctly configured before starting the backend.

## Frontend Setup

Open another terminal and navigate to the frontend:

```bash
cd frontend
```

Install the npm dependencies:

```bash
npm install
```

Start the Angular development server:

```bash
ng serve
```

The application will be available at:

```text
http://localhost:4200/
```

The application automatically reloads when source files are modified.

## Build

### Frontend

To create a production build:

```bash
ng build
```

The generated files will be available in the `dist/` directory.

### Backend

To build the Spring Boot application:

```bash
./mvnw clean package
```

## Testing

### Frontend Unit Tests

Run the Angular tests with:

```bash
ng test
```

## API

The backend provides REST APIs used by the Angular frontend for:

* Authentication
* User management
* Course management
* Course enrollment
* Learning content
* Quizzes
* Meetings
* Progress tracking
* Notifications

## Future Improvements

Possible future improvements include:

* Online video conferencing
* Advanced learning analytics
* Course recommendations
* In-app real-time notifications
* Digital certificates

## Repository

[View the project on GitHub](https://github.com/sirineelayeb/E-Learning-Platform-Project)

## Contributing

Contributions are welcome.

To contribute:

1. Fork the repository.
2. Create a feature branch:

```bash
git checkout -b feature/your-feature
```

3. Commit your changes:

```bash
git commit -m "Add your feature"
```

4. Push your branch:

```bash
git push origin feature/your-feature
```

5. Open a Pull Request.

## License

This project was developed for educational and development purposes.
