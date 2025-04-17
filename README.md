# Simple Minds Quiz Application

## Description

The **Simple Minds Quiz Application** is a Java-based quiz game built using Swing for the graphical user interface (GUI). This project features a login screen, a set of quiz questions, a timer, lifeline options, and a scoring system.

### Key Features:
- **Login Screen**: Users can enter their name to start the quiz.
- **Quiz**: A set of 10 multiple-choice questions.
- **Timer**: A 15-second countdown for each question.
- **Lifeline**: A 50-50 lifeline that eliminates two wrong answers.
- **Scoring**: Users are awarded points for correct answers.
- **Rules**: The game provides rules before starting.

## Technologies Used

- **Java**: Programming language used to build the application.
- **Swing**: GUI library used to create the application's interface.
- **JDK 8+**: The project is compatible with JDK 8 or higher.

## Setup Instructions

### Prerequisites
- Java Development Kit (JDK) 8 or higher installed on your system.
- An IDE or text editor of your choice (e.g., IntelliJ IDEA, Eclipse, or VS Code).

### Steps to Run the Application

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/simple-minds-quiz.git
    ```

2. Navigate to the project directory:
    ```bash
    cd simple-minds-quiz
    ```

3. Open the project in your preferred IDE.

4. Run the `Login` class to start the application:
    - The application will prompt you to enter your name.
    - Once the name is entered, it will take you to the quiz.
    
5. Answer the questions and use the 50-50 lifeline if needed.

## Screenshots

### Login Screen
![Login Screen](screenshots/login_screen.png)

### Quiz Screen
![Quiz Screen](screenshots/quiz_screen.png)

## File Structure

- **Login.java**: Contains the code for the login screen.
- **Quiz.java**: Contains the main quiz logic and UI components.
- **Rules.java**: Displays the game rules.
- **icons/**: Directory containing image resources used in the app (e.g., `login.jpeg`, `quiz.jpg`).

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-xyz`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-xyz`).
6. Open a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- Thanks to the contributors for their valuable feedback and suggestions.
- Swing for building the UI components.
- The icons used are sourced from free resources.

---

Feel free to contribute, suggest features, or file issues for any bugs you encounter.
