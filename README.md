# 📇 Smart Contact Manager

A feature-rich contact management system built with **Spring Boot**, enabling users to securely manage their contacts with advanced functionalities like cloud storage, email integration, and social login.

---

## 🛠️ Features

- **User Authentication**:
  - Signup with email and password.
  - Email verification for account activation.
  - Social login using Google and GitHub (OAuth).

- **Contact Management**:
  - Add, view, update, and delete contacts with pictures (uploaded to AWS/Cloudinary).
  - Mark contacts as favorites.
  - Search and filter through contacts.

- **Email Integration**:
  - Compose and send emails with text and attachments.

- **User Profile**:
  - View and update profile details.
  - Toggle between light and dark themes.

- **Data Management**:
  - Paginated display for efficient contact management.
  - Export contact data to Excel.

- **Feedback System**:
  - Users can provide feedback directly from the app.

---

## 🚀 Getting Started

### Prerequisites

- **Java** 17 or higher
- **Maven** 3.6 or higher
- **Spring Boot** 3.x
- **MySQL/PostgreSQL** database
- AWS/Cloudinary account for image storage

---

### 🔧 Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Maeinukhan63/SCM.git
    cd SCM
    ```

2. **Configure application properties**:
    Update `src/main/resources/application.properties` with your database and cloud storage configurations.

3. **Build the project**:
    ```bash
    mvn clean install
    ```

4. **Run the application**:
    ```bash
    mvn spring-boot:run
    ```
    Alternatively, run the JAR file created in the `target` directory:
    ```bash
    java -jar target/smart-contact-manager-0.0.1-SNAPSHOT.jar
    ```

---

## 🌐 Usage

- **Access the Application**:  
  The application runs on `http://localhost:8080` by default. Interact with the app through its user-friendly web interface.

### Core Functionalities
- **User Authentication**:
  Secure login and registration with options for social login using Google and GitHub.
  
- **Contact Management**:
  Add, view, update, delete, and search contacts. Upload and store contact photos in the cloud.

- **Email Services**:
  Send emails with text and attachments directly from the app.

- **Data Export**:
  Export contact information to Excel for offline use.

---

### Project Structure
bash
Copy
Edit
SmartContactManager/
├── src/main/java/com/maeinukhan63/scm/
│   ├── controller/        # Contains all controllers (user, admin)
│   ├── model/             # Entity classes (User, Contact)
│   ├── repository/        # Repositories for database interaction
│   ├── service/           # Business logic
│   ├── config/            # Spring Security and other configurations
├── src/main/resources/
│   ├── static/            # Static resources (CSS, JS, images)
│   ├── templates/         # Thymeleaf templates
├── application.properties # Configuration file



---

### Setup Instructions
### Prerequisites

Java 17 or higher
Maven (for dependency management)
MySQL/PostgreSQL database
AWS/Cloudinary account for cloud storage


### Steps to Run the Project
Clone the repository:
git clone https://github.com/Maeinukhan63/SCM.git

Navigate to the project directory:
cd SCM

Configure the database in application.properties:

properties
spring.datasource.url=jdbc:mysql://localhost:3306/scm
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

Add your Cloudinary/AWS credentials to the configuration file.

Build and run the application:
mvn clean install
mvn spring-boot:run

Access the application in your browser:
http://localhost:8080

---

### Contributing
Contributions are welcome! If you'd like to improve this project:

1.Fork the repository.
2.Create a feature branch:
git checkout -b feature-name

3.Commit your changes:
git commit -m "Added new feature"

4.Push to the branch:
git push origin feature-name

5.Open a pull request.

 ### Contact
If you have any questions or suggestions, feel free to contact me:

GitHub: Maeinukhan63
Email: khanmaeinuddin19@gmail.com
