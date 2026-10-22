# StudyPilot-Smart-Study-Planner

**StudyPilot** is a simple, interactive student productivity website designed to help students estimate their study workload, plan around deadlines, and receive personalised study recommendations.

## Overview

Managing multiple subjects and deadlines can be challenging. StudyPilot helps students understand how much time they need to complete their remaining chapters and whether their current study schedule is realistic.

The website provides instant calculations based on the information entered by the user, making study planning easier and more organised.

## Features

- **Study Workload Prediction:** Estimates the total study hours required based on remaining chapters and hours per chapter.
- **Completion Time Estimation:** Calculates the approximate number of study days needed.
- **Deadline Analysis:** Compares the estimated workload with the available study time before the deadline.
- **Study Recommendations:** Suggests practical ways to manage workload and prioritise chapters.
- **Deadline Readiness Indicator:** Displays a visual progress bar representing available study capacity relative to the estimated workload.
- **Responsive Design:** Provides a clean dashboard experience on desktop and mobile screens.
- **Instant Results:** Calculates and displays results without reloading the page.

## Tech Stack

- **HTML5** — Website structure
- **CSS3** — Styling, responsive layout, and dashboard design
- **JavaScript** — Calculations, prediction logic, and interactive features

## How It Works

1. Enter the subject name.
2. Specify the number of chapters remaining.
3. Enter the estimated hours required per chapter.
4. Set the number of hours available for studying each day.
5. Select your deadline.
6. Click **Predict My Study Plan** to view the results.

StudyPilot calculates the total workload, estimates the required study days, evaluates the available study time, and displays recommendations based on the results.

## Prediction Logic

The project uses a simple rule-based calculation system.

- **Total Workload** = Remaining Chapters × Hours per Chapter
- **Estimated Study Days** = Total Workload ÷ Daily Study Hours, rounded up
- **Available Study Hours** = Days Until Deadline × Daily Study Hours
- **Deadline Status** = Compares estimated workload with available study hours

These calculations provide planning estimates based on user input. Actual study duration may vary depending on the subject's difficulty, revision requirements, and individual learning pace.

**Note:** StudyPilot currently uses rule-based logic rather than a trained machine learning model.

## Getting Started

No additional software packages or backend setup are required.

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in your web browser.

Alternatively, open the folder in Visual Studio Code and run the page using the Live Server extension.

## Project Structure

```text
StudyPilot/
└── index.html
```

The HTML file contains the website structure, CSS styling, and JavaScript functionality in one place.

## Future Improvements

- Add a study progress tracker for completed chapters.
- Support multiple subjects in a single study plan.
- Generate a daily study timetable.
- Save study plans using browser local storage.
- Improve recommendations using subject difficulty and revision time.
- Explore machine learning for more advanced workload predictions.

## Author

Developed as a student productivity and web development project to explore interactive dashboards, JavaScript-based calculations, and rule-based prediction systems.

---

**StudyPilot — Plan with purpose, learn with confidence.**
