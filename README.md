# Moviewise

## Overview
This project is a web application that helps people manage their movie collections. The backend is built with Java and MongoDB, while the frontend is developed using React and JavaScript.

## Screenshot
![313462616-76ffc4d0-7a87-46df-8b92-f60942a719a7](https://github.com/user-attachments/assets/698241ba-8698-4bdc-a90d-2b335bb74246)

## Technologies

### Backend
- **Java**: A high-level, class-based, object-oriented programming language designed to have as few implementation dependencies as possible.
- **MongoDB**: A source-available cross-platform document-oriented database program.
- **Spring Boot**: A framework that simplifies the development of new Spring applications, providing a range of non-functional features common to large classes of projects.
- **Lombok**: A Java library that automatically plugs into your editor and build tools, spicing up your Java.
- **Spring Data MongoDB**: A part of the larger Spring Data family, makes it easy to implement MongoDB-based repositories.
- **Spring Dotenv**: A library to load environment variables from a `.env` file into the Spring application context.

### Frontend
- **React**: A JavaScript library for building user interfaces, maintained by Facebook and a community of individual developers and companies.
- **Vite**: A build tool that aims to provide a faster and leaner development experience for modern web projects.
- **Axios**: A promise-based HTTP client for the browser and Node.js.
- **React Router**: A collection of navigational components that compose declaratively with your application.
- **Emotion**: A library designed for writing css styles with JavaScript.
- **Bootstrap**: A free and open-source CSS framework directed at responsive, mobile-first front-end web development.
- **Material-UI**: A popular React UI framework.
- **ESLint**: A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.

## Getting Started

### Prerequisites
- Java 17 or later
- Node.js 14.x or later
- MongoDB 4.4 or later

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/erkindilekci/moviewise.git
   cd moviewise
   ```

2. **Backend Setup:**
   ```sh
   cd server
   ./mvnw clean install
   ```

3. **Frontend Setup:**
   ```sh
   cd client
   npm install
   npm run dev
   ```

### Running the Application

1. **Start the Backend:**
   ```sh
   cd server
   ./mvnw spring-boot:run
   ```

2. **Start the Frontend:**
   ```sh
   cd client
   npm run dev
   ```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
