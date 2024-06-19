# React Quiz 🎉

Welcome to the React Quiz application! This project is a simple and interactive quiz built with React, designed to test your knowledge and mastery of React concepts. 🚀

## Features
<ul>
  <li> <b>Dynamic Questions:</b> Fetches questions from a local server.</li>
  <li> <b>Timer:</b> Keeps track of the time left for each question.</li>
  <li> <b>Progress Tracker:</b> Shows the current question number and points earned.</li>
  <li> <b>Error Handling:</b> Displays an error message if there's an issue fetching questions.</li>
  <li> <b>High Scores:</b> Keeps track of the highest score achieved.</li>
  <li> <b>Engaging UI:</b> Fun and interactive design with emojis based on performance.</li>
</ul>

## Technologies Used
<ul>
  <li> <b>React: </b>A JavaScript library for building user interfaces.</li>
   <li> <b>useReducer Hook: </b>Manages complex state logic.</li>
   <li> <b>useEffect Hook: </b>Handles side effects like data fetching.</li>
   <li> <b>CSS: </b>Styles the components for a better user experience.</li>
   <li> <b>json-server: </b>A full fake REST API for serving quiz questions.</li>
</ul>

## Installation

To run this project locally, follow these steps:

### Clone the repository:
git clone https://github.com/your-username/react-quiz.git
cd react-quiz

### Install dependencies:
npm install

### Start the local server:
Make sure you have a server running at http://localhost:8000 that serves the questions in JSON format. You can use a tool like json-server for this:
npm install -g json-server
json-server --watch db.json --port 8000

### Run the application:
npm start

## File Structure
Here's a quick overview of the file structure:
react-quiz/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Error.js
│   │   ├── FinishScreen.js
│   │   ├── Footer.js
│   │   ├── Header.js
│   │   ├── Loader.js
│   │   ├── Main.js
│   │   ├── NextButton.js
│   │   ├── Progress.js
│   │   ├── Question.js
│   │   ├── StartScreen.js
│   │   ├── Timer.js
│   │   └── index.js
│   ├── App.js
│   ├── index.css
│   └── index.js
├── questions.json
├── package.json
└── README.md

## Screenshots
![Screenshot 2024-06-18 231226](https://github.com/Ankita7238/React-Quiz/assets/141292926/4d1b5081-7af9-41a3-b19f-81ced8eded6a)

![Screenshot 2024-06-18 232758](https://github.com/Ankita7238/React-Quiz/assets/141292926/5df34f1e-2253-42ab-904a-ebacdedc23e9)

![Screenshot 2024-06-18 232926](https://github.com/Ankita7238/React-Quiz/assets/141292926/e7c4102f-c556-48ff-9480-160525604e3e)

![Screenshot 2024-06-18 233114](https://github.com/Ankita7238/React-Quiz/assets/141292926/bb4df68a-2068-4298-9ee1-4e7726f0df7f)





