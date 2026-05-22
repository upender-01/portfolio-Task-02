---

# Styled Portfolio Website

## Project Overview

* This project is a personal portfolio website designed to showcase web development skills, educational background, and contact information.


* The primary objective was to build a modern, visually appealing, and highly responsive single-page application using pure HTML and CSS.


* The design focuses on user experience by implementing modern UI trends such as glassmorphism, smooth scrolling, and interactive hover states.



---

## Setup Instructions

To run and test this project locally, follow these simple steps:

* Create a main project folder named `Portfolio-Project`.


* Inside this folder, create a file named `index.html` and paste the provided HTML code into it.


* Create a second file named `style.css` in the same directory and paste the upgraded CSS code into it.


* Create a subfolder named `images` and place your placeholder images inside it (e.g., `profile.jpg`, `skills.jpg`, `backend.jpg`, `programming.jpg`).


* Double-click `index.html` to open it in your default web browser, or use an extension like VS Code Live Server for hot-reloading.



---

## Code Structure

The project follows a clean and standard front-end file hierarchy to separate structure from presentation.

* **`index.html`**: Contains the semantic markup of the page, divided into functional sections (Header, Hero, About, Skills, Profiles, Contact).


* **`style.css`**: The external stylesheet containing all visual styling, custom variables, layout rules, and media queries.


* **`images/`**: A dedicated directory for storing all graphical assets used on the site.



---

## Technical Details & Features

* **Modern Layouts**: Flexbox is utilized extensively for one-dimensional alignments, such as centering elements in the header, hero section, and contact form. CSS Grid is employed in the Skills section to create a responsive, auto-fitting, two-dimensional card layout.


* **UI Design**: The UI incorporates a custom CSS variable (`:root`) color scheme utilizing blues, slates, and an off-white background for consistency. Advanced visual elements include a glassmorphism (frosted glass) sticky header, modern blue-to-purple text gradients, and pill-shaped call-to-action buttons.


* **Responsiveness**: Mobile responsiveness is handled via CSS `@media` queries. For screens under 768px, the layout adapts by converting flex directions to columns, stacking the header and hero items, and adjusting typography sizes for readability.


* **Interactive Architecture**: The site includes smooth scrolling for anchor links and CSS keyframe animations (like `@keyframes fadeUp`) to gracefully slide elements into view upon loading.
