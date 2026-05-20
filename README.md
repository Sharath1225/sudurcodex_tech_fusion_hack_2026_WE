# EcoSort – Smart Waste Segregation & Quiz System

Project Overview

EcoSort is an interactive waste segregation web application designed to help users identify the correct waste disposal category using an intelligent search system and an engaging quiz platform.

The project promotes environmental awareness by educating users about:

* Organic waste
* Recyclable waste
* Hazardous waste
* Residual waste

Users can:

* Search for waste items
* Get instant bin recommendations
* Learn disposal explanations
* Take quizzes to test their knowledge
* Explore categorized waste management guides

---

Features

Smart Waste Search

* Search waste items like:

  * Apple peels
  * Plastic bottles
  * Batteries
  * Diapers
* Instant suggestions while typing
* Displays:

  * Correct bin category
  * Bin color
  * Disposal explanation

Waste Categories

The system classifies waste into:

| Category   | Bin Color | Description                     |
| ---------- | --------- | ------------------------------- |
| Organic    | Green     | Compostable biodegradable waste |
| Recyclable | Blue      | Reusable recyclable materials   |
| Hazardous  | Red       | Toxic and chemical waste        |
| Residual   | Black     | Non-recyclable landfill waste   |


Interactive Quiz System

* Randomly selects 10 questions
* Multiple-choice quiz
* Instant feedback
* Progress tracking
* Final score display
* Restart functionality

Modern UI Features

* Animated buttons
* Hover effects
* Responsive layout
* Progress bars
* Highlighted waste category cards
* Smooth transitions and animations


Technologies Used

Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

Project Structure

bash
EcoSort/
│
├── home.html
├── quiz.html
├── style.css
├── script.js
├── images/
│   └── dustbin.jpeg
└── README.md


How It Works

1. Waste Search System

The application contains a large waste database object:

```javascript
const wasteDatabase = {
   "apple": {
      category: "Organic (Green)",
      color: "#27ae60",
      description: "Fruit scraps are biodegradable."
   }
}
```

When a user searches:

* Input is matched with the database
* Correct category is displayed
* Relevant card is highlighted

---

2. Quiz Engine

Quiz questions are stored in an array:

```javascript
var allQuizQuestions = [
   {
      question: "Which bin should you use for fruit peels?",
      options: [...],
      hint: "Fruit peels are biodegradable."
   }
]
```

Features include:

* Randomized questions
* Score tracking
* Navigation control
* Result summary

---

UI Highlights

Animated Components

* Pulsing quiz icons
* Hover scaling effects
* Smooth button animations
* Progress bar animations

Responsive Design

The website is fully responsive and works on:

* Desktop
* Tablet
* Mobile devices

---

Educational Purpose

This project helps users:

* Learn proper waste segregation
* Understand environmental sustainability
* Practice responsible disposal habits

---

## 🔮 Future Enhancements

Possible future improvements:

* AI-based image waste detection
* Voice search support
* User authentication
* Leaderboard system
* Database integration
* Admin dashboard
* Multi-language support

---

Screens Included

* Home Page
* Waste Search Section
* Quiz Page
* Waste Category Cards
* Search Suggestions

---

Sample Waste Items Supported
Organic

* Fruit peels
* Bread
* Tea bags
* Coffee grounds

Recyclable

* Plastic bottles
* Newspapers
* Cardboard
* Glass jars

Hazardous

* Batteries
* Paint
* Medicines
* Electronics

Residual

* Diapers
* Wrappers
* Dust
* Thermocol

---


Author

Developed as an environmental awareness by Sharath, Amith S Devadiga, Akhilesh Shetty, Pranav
---
License

This project is created for educational and awareness purposes.
