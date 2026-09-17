# What's For Dinner

A responsive web application that solves the daily question: **"What should I cook today?"**

The app randomly picks a recipe from a curated collection of 19 dishes and displays everything you need to cook it — from ingredients and step-by-step instructions to nutrition facts and professional chef tips.

---

## Features

- Random recipe generator with a "Try Another Recipe" button
- High-quality dish image, rating, and review count
- Prep time, cook time, servings, difficulty, and cuisine category
- Tabbed interface with four sections:
  - **Ingredients** — numbered list of what you need
  - **Instructions** — step-by-step cooking guide
  - **Nutrition** — calories, protein, carbs, fat, fiber, sodium
  - **Chef's Tips** — professional advice for better results
- Automatic warning for recipes that take more than 45 minutes
- Fully responsive design for desktop and mobile
- Custom CSS with gradients, shadows, and smooth transitions

---

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — Flexbox, media queries, transitions
- **JavaScript (ES5)** — vanilla JS, no frameworks or libraries
- **Font Awesome 6** — icon set

---

## Project Structure
whats-for-dinner/
├── index.html
├── CSS/
│ └── style.css
├── JS/
│ ├── Meals.js # Recipe data (19 dishes)
│ └── App.js # App logic and DOM manipulation
└── assets/
├── favicon.png
├── Meals Data.txt
├── avatar-4.jpg
└── meals/
├── meal-01.jpg
├── meal-02.jpg
├── ...
└── meal-19.jpg

---

## How to Run

1. Clone the repository
2. Open `index.html` in your browser
3. No build step, no dependencies, no installation required
