
# ShopElectro

ShopElectro is a full-stack e-commerce application designed for shopping electronic devices. It features a robust backend developed in Spring Boot, a dynamic frontend built with React.js, and end-to-end testing capabilities powered by Selenium.

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

---

## Features

### Frontend
- Responsive user interface built with **React.js** and **Vite**.
- State management with **Redux Toolkit** slices.
- Dynamic routing and seamless user experience.

### Backend
- RESTful API services developed in **Spring Boot**.
- Supports authentication and CRUD operations.
- **MySQL/PostgreSQL** database integration.

### Testing
- **Selenium** for automated end-to-end testing.
- Unit testing with **JUnit** for backend services.

---

## Technologies Used

### Frontend
- React.js
- Vite
- Redux Toolkit
- CSS/SCSS

### Backend
- Spring Boot
- Selenium
- JUnit
- MySQL/PostgreSQL

---

## Setup Instructions

### Prerequisites
- Node.js and npm installed for the frontend.
- Java 11+ and Maven installed for the backend.
- MySQL/PostgreSQL installed for the database.

### Backend Setup
1. Clone the repository and navigate to the backend folder:
   ```bash
   git clone <repository-url>
   cd ShopElectro/backEnd
   ```
2. Install dependencies:
   ```bash
   mvn clean install
   ```
3. Configure the database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/shop_electro
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```
4. Start the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```bash
   cd ShopElectro/frontEnd
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open the application in your browser at `http://localhost:3000`.

---

## Testing

### End-to-End Testing with Selenium
- Navigate to the `backEnd` folder and run the Selenium tests:
  ```bash
  mvn test
  ```

### Unit Tests
- Backend services have unit tests written using JUnit. Run them with:
  ```bash
  mvn test
  ```

---

## Contributing

Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).
