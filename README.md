# Vanilla JS Mini Calculator

A sleek, fully functional mini web calculator built using pure HTML5, CSS3, and Vanilla JavaScript. This project was developed as a hands-on exercise to master core frontend fundamentals, DOM manipulation, responsive UI layouts, and custom keyboard-free accessibility workflows.

---

##  Features
* *Full Math Operations:* Handles addition, subtraction, multiplication, division, and decimals.
* *Glassmorphism Design:* Styled with a modern aesthetic featuring backdrop-filter blurs, radial gradients, and fluid drop shadows.
* *CSS Grid Layout:* Uses a perfectly structured $4 \times 4$ grid system for clean, uniform button alignments.
* *Error Handling:* Protects against invalid math equations (e.g., dividing by zero or broken syntax) by gracefully displaying an Error message.
* *Fully Responsive:* Centered flexbox viewport layout that works comfortably across different screens.

---

##  Tech Stack & Concepts Applied

###  Frontend Fundamentals
* *HTML5:* Semantic architecture using dedicated input types, structural wrappers (div), and inline click listeners.
* *CSS3:* Built using Flexbox, CSS Grid (grid-template-columns: repeat(4, 1fr)), advanced box-shadow behaviors (inset), hover scales, and transitions.

###  JavaScript Logic (Vanilla JS)
* *DOM Selection:* Interacting directly with the UI layout via document.getElementById().
* *State Management:* Dynamically tracking, clear-wiping, and updating string concatenation inside the display buffer.
* *Exception Handling:* Using try...catch blocks paired with the standard native execution engine to evaluate math computations reliably.

---

##  Project Structure
```text
vanilla-js-calculator/
├── index.html   # Markup structure and UI event handlers
├── style.css    # Layout styling, glassmorphism aesthetics & animations
└── script.js    # Computational logic and display controls
