# Vanilla JS Mini Calculator

A sleek, fully functional mini web calculator built using pure HTML5, CSS3, and Vanilla JavaScript. This project was developed as a hands-on exercise to master core frontend fundamentals, DOM manipulation, responsive UI layouts, and custom keyboard-free accessibility workflows.

---

##  Features
* *Full Math Operations:* Handles addition, subtraction, multiplication, division, percentage, decimal, and sign toggle.
* *Backspace Functionality:* Easily delete the last entered character without clearing the entire expression.
* *Glassmorphism Design:* Styled with a modern aesthetic featuring backdrop-filter blurs, radial gradients, and fluid drop shadows.
* *Responsive CSS Grid Layout:* Built with a clean $4 \times 4$ grid that adapts smoothly to different screen sizes and devices.
* *Error Handling:* Protects against invalid math equations (e.g., dividing by zero or broken syntax) by gracefully displaying an Error message.
* *Fully Responsive:* Fully responsive layout centered with Flexbox for a consistent experience across desktops, tablets, and smartphones.

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
