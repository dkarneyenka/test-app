# Quiz CLI

Quiz CLI is an interactive command-line quiz game built using Node.js. The quiz is designed to test your programming knowledge and improve your skills in a fun and engaging way.

## Project Overview

This project demonstrates the following concepts:
- **Interactive CLI Application:** Developed to provide users with a seamless quiz experience in the terminal.
- **Modern JavaScript Features:** Utilizes ES Modules, async/await, Promises, and array methods.
- **Modular Architecture:** The source code is divided into self-contained, reusable modules.
- **Learning Categories:** Organized programming quizzes on topics like JavaScript, Node.js, and general programming concepts.

## Features
- Multiple-choice programming questions from various categories (e.g., JavaScript Basics, Node.js Fundamentals).
- Immediate feedback on answers along with explanations.
- Customizable number of quiz questions.
- Color-coded terminal output using ANSI escape codes for a visually engaging experience.

---

## Setup Instructions

### Prerequisites
- Node.js version `18.0.0` or newer must be installed on your system.

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/quiz-cli.git
   cd quiz-cli
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

---

## Usage

To start the quiz, run the following command:
```bash
npm start
```

Once the application starts:
1. Choose a category to play.
2. Specify the number of questions you want to attempt.
3. Answer the questions by entering the number corresponding to your choice.

### Example:
```bash
Choose a category:
1. JavaScript Basics
2. Node.js Fundamentals
3. General Programming

Your choice (enter number): 1
```

You'll receive immediate feedback on your responses, and explanations will be provided for incorrect answers.

---

## File Structure
### Root Files
- `index.js`: The entry point of the application handling the main CLI logic.
- `package.json`: Contains metadata about the project and its dependencies.

### Directories
1. **`data`**:
   - `questions.json`: A JSON file containing available questions, options, answers, and explanations.

2. **`src`**:
   - `colors.js`: Defines terminal colors using ANSI escape sequences.
   - `input.js`: Handles user input via the Node.js Readline module.
   - `quiz.js`: Contains the `Quiz` class which manages quiz logic and scoring.

---

## Questions Data

The quiz questions are stored in `data/questions.json`, categorized by topics like `JavaScript Basics`, `Node.js Fundamentals`, and `General Programming`. Each category has multiple questions, options, correct answers, and detailed explanations.

---

## Contribution

We welcome contributions! If you'd like to add new features or quiz questions, please fork the project and submit a pull request. Ensure your code follows the existing conventions and includes thorough comments.

### Guidelines
- Follow the established coding style in the project.
- Ensure new questions have clear options, a correct answer, and an explanation.
- Update the documentation when applicable.

---

## License

This project is licensed under the MIT License.

---

### Important Notes
This project is standalone and purely educational, intended to enhance programming knowledge in a fun and engaging way.