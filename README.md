
# Interactive Quiz

This project, you will design and implement an interactive quiz using React and CSS The goal is to create a user-friendly quiz application that allows participants to answer
multiple-choice questions and receive their scores at the end.




## Features


- Display of multiple-choice questions.
- Radio button selection with visual feedback.
- Score calculation and user performance feedback.
- Tracks high score.
- Dynamic questions from JSON.
- Styled and responsive layout.
- Questions and answers are stored in a structured JavaScript array of objects.
- Each object contains the question text, multiple  options, and the correct answer.

## New Feature


- Add a timer to limit the time for each question.

- Track and display the highest score achieved during the session.
- Compare the current score with the previous high score.
- Automatically update the high score if the user beats it.
- Stored using browser localStorage for session persistence.
## System Modules
### 1. Quiz Module
- Renders questions and answer choices dynamically from a question bank.
- Allows answer selection using radio buttons.
- Submits answers and calculates the score.

### 2. Result Module
- Displays the total score.
- Shows feedback based on user performance.
- Compares score with high score and updates if necessary.

### 3. High Score Module
- Stores and retrieves the highest score using localStorage.
- Displays high score on the result screen.

### 4. UI Module
- Manages quiz layout, spacing, colors, and fonts using CSS.
- Provides visual feedback for selected answers and results.

### 5. Answer Feedback Module

- Highlights the selected answer once chosen.
- On submission:
  - Shows whether the selected answer is correct or incorrect.
  - Displays the correct answer if the user selected incorrectly.
- Uses color cues (e.g., green for correct, red for incorrect) for visual feedback.
- Enhances learning by giving immediate clarity on performance.


## Tech Stack

- **Frontend**: React (Create React App)
- **Backend**: json-server (Mock API)
- **Others**: HTML, CSS, JavaScript

##  Installation


To run this project locally, follow these steps:

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Athira-vk/Quiz-App-.git
```

---

### 2️⃣ Install Project Dependencies


####  Frontend 

```bash
npm install
```

---

### 3️  Install Backend Dependencies (json-server)

In your `package.json`, ensure the following script is included:

```json
"scripts": {
  "start": "react-scripts start",
  "server": "json-server --watch data/questions.json --port 8000"
}
```
This will start the mock API on http://localhost:8000/questions and serve data from the data/questions.json file.

---


### 4️⃣  Start the JSON Server


Run the following command to start the JSON server, which will provide the mock data:

```bash
npm run server
```
---

### 5️⃣ Start the React App

```bash
npm start
```

---

### ✅ Application Running

- **Quiz:** http://localhost:3000
- **JSON server API:** http://localhost:8000/questions 




---

    
## Screenshots

                          
### 🏠 Landing Page
![Landing Page](https://github.com/user-attachments/assets/861dcedb-376c-458c-a9c7-ba631c45856b)

### 🚀 Start the Quiz
![Start the Quiz](https://github.com/user-attachments/assets/2f8f618c-6422-49d7-bc67-d8586edb5bc1)

### ✅ Answer Selected
![Answer Selected](https://github.com/user-attachments/assets/ee7088e9-f316-4992-88c3-cb2d12367aae)

### 🧮 Score Displayed Successfully
![Score displayed successfully](https://github.com/user-attachments/assets/d3a96d94-a6f2-4262-83ee-d62c1eb361d1)
