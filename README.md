# QuizApp 🎯

A Spring Boot-based programming quiz application designed to help developers test their knowledge in Java, Python, and C programming languages.

## 📋 Overview

QuizApp is a monolithic web application that provides an interactive platform for programming enthusiasts to take quizzes and assess their coding knowledge. The application currently supports questions across three major programming languages.

## ✨ Features

- 📚 Multiple programming language support (Java, Python, C)
- ❓ Interactive quiz interface
- 🎓 Programming knowledge assessment
- 💾 Question and quiz management
- 🔄 RESTful API architecture

## 🛠️ Tech Stack

- **Framework**: Spring Boot
- **Language**: Java
- **Build Tool**: Maven
- **Architecture**: Monolithic (planned migration to microservices)

## 📁 Project Structure

```
QuizApp/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.telusko.quizapp/
│   │   │       ├── controller/     # REST controllers
│   │   │       ├── dao/            # Data access objects
│   │   │       ├── model/          # Entity models
│   │   │       └── service/        # Business logic
│   │   │           ├── QuestionService
│   │   │           ├── QuizService
│   │   │           └── QuizAppApplication
│   │   └── resources/
│   │       ├── static/
│   │       ├── templates/
│   │       └── application.properties
│   └── test/
├── .gitignore
├── pom.xml
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.6+
- IDE (IntelliJ IDEA recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/QuizApp.git
cd QuizApp
```

2. Build the project:
```bash
mvn clean install
```

3. Run the application:
```bash
mvn spring-boot:run
```

4. Access the application at `http://localhost:8080`

## 🔧 Configuration

Update `src/main/resources/application.properties` with your database configurations:

```properties
spring.application.name=QuizApp
# Add your database configuration here
```

## 📝 API Endpoints

*Documentation in progress...*

### Questions
- `GET /questions` - Get all questions
- `POST /questions` - Create a new question
- `GET /questions/{id}` - Get question by ID

### Quiz
- `GET /quiz` - Get all quizzes
- `POST /quiz/create` - Create a new quiz
- `GET /quiz/{id}` - Get quiz by ID

## 🚧 Development Status

This project is currently under active development. Planned features and improvements:

- [ ] User authentication and authorization
- [ ] Quiz result tracking and analytics
- [ ] Timer functionality for quizzes
- [ ] Difficulty levels for questions
- [ ] Admin dashboard for question management
- [ ] Migration to microservices architecture
- [ ] More programming languages (JavaScript, C++, etc.)

## 🏗️ Upcoming Migration

This application is being prepared for migration from a monolithic architecture to a microservices-based architecture as part of a learning course.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Chamath Rupasinghe**
- Learning Spring Boot and Microservices
- Location: Kandy, Sri Lanka
- Guided by: Telusko

## 📞 Contact

For questions or feedback, please open an issue in the GitHub repository.

---

⭐ If you find this project helpful, please consider giving it a star!

**Note**: This is a learning project and is continuously being improved.
