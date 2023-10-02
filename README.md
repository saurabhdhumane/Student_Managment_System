# Student Management System

## Overview

The Student Management System is a Java Spring Boot web application designed to manage student records. This application provides REST APIs for basic CRUD (Create, Read, Update, Delete) operations on student data and includes a web interface for easy interaction.

## Features

- Create, Read, Update, and Delete student records.
- List all available student records.
- Simple and intuitive web interface.
- Uses Spring Boot for backend REST APIs and Spring MVC for the web interface.
- MySQL database for data storage.
- Utilizes Spring Data JPA for database interaction.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/saurabhdhumane/student_managemen_system.git
   ```

2. Import the project into your favorite Java IDE (e.g., IntelliJ IDEA or Eclipse).

3. Configure your MySQL database settings in `application.properties`:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/sms?useSSL=false&serverTimezone=UTC&useLegacyDatetimeCode=false
   spring.datasource.username=root
   spring.datasource.password=root
   ```

4. Run the application.

## Usage

1. Access the web interface by opening a web browser and navigating to `http://localhost:8080`.

2. Use the API endpoints to interact with the system programmatically:

   - `GET /api/students`: Retrieve a list of all students.
   - `GET /api/students/{id}`: Retrieve a student by ID.
   - `POST /api/students`: Create a new student.
   - `PUT /api/students/{id}`: Update an existing student.
   - `DELETE /api/students/{id}`: Delete a student by ID.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

If you have any questions or feedback, feel free to reach out to saurabhdhumneraje@gmail.com.
