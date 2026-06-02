# FAQ Accordion

A professional and responsive FAQ Accordion component built using HTML, CSS, and JavaScript.

This project allows users to interact with a list of frequently asked questions through an accordion interface. When a question is selected, its corresponding answer expands while any previously opened section automatically collapses. This creates a clean, organized, and user-friendly experience.

The project focuses on JavaScript DOM manipulation, event handling, UI animations, and responsive frontend development.

---

## Features

### Accordion Functionality

- Expand and Collapse FAQ Items
- Only One Section Open at a Time
- Smooth Open/Close Animation
- Interactive Toggle Icons
- Clean and Organized Layout

### User Interface

- Professional Design
- Modern Card Layout
- Responsive Structure
- Mobile-Friendly Experience
- Consistent Typography and Spacing

### JavaScript Functionality

- DOM Manipulation
- Event Listeners
- Dynamic Class Management
- Accordion State Control

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Flexbox
- CSS Transitions
- Responsive Design

---

## Project Objectives

This project was created to practice:

- DOM Manipulation
- Event Handling
- Interactive User Interfaces
- Responsive Web Design
- CSS Animations
- Frontend Development Fundamentals

---

## How It Works

### Default State

- The first FAQ item is expanded by default.
- All other FAQ items remain collapsed.

### Opening an Item

When a user clicks a question:

1. The selected answer expands.
2. Any previously opened answer collapses.
3. The icon rotates to indicate the active state.

### User Experience

This approach ensures:

- Better readability
- Reduced clutter
- Improved navigation
- Professional presentation

---

## Project Structure

```bash
FAQAccordion_BimaRahmadhani/
│
├── index.html
├── style.css
└── script.js
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/FAQAccordion_BimaRahmadhani.git
```

### Open Project Folder

```bash
cd FAQAccordion_BimaRahmadhani
```

### Run Project

Simply open:

```bash
index.html
```

in your preferred browser.

---

## Core JavaScript Concepts Used

### DOM Selection

```javascript
document.querySelectorAll()
```

### Event Handling

```javascript
addEventListener("click")
```

### Class Manipulation

```javascript
classList.add()
classList.remove()
classList.toggle()
```

### Accordion Logic

```javascript
if (accordion !== item) {
    accordion.classList.remove("active");
}
```

---

## Responsive Design

The application is optimized for:

- Desktop
- Laptop
- Tablet
- Mobile Devices

Responsive features include:

- Flexible Container Layout
- Adaptive Typography
- Mobile-Friendly Spacing
- Responsive Accordion Elements

---

## Learning Outcomes

After completing this project, you will understand:

- How to build accordion interfaces
- How to manipulate elements using JavaScript
- How to handle user interactions
- How to create smooth UI transitions
- How to structure responsive layouts
- How modern FAQ systems work

---

## Future Improvements

Potential enhancements include:

- FAQ Search Functionality
- Category Filtering
- Dark Mode Support
- Keyboard Accessibility
- ARIA Accessibility Enhancements
- Remember Last Opened Item
- Multi-Level Accordions
- API-Based FAQ Content

---

## Author

**Bima Rahmadhani**

Frontend Developer

---

## License

This project is open-source and available for educational and personal use.
