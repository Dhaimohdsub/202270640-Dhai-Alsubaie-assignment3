# Technical Documentation — Assignment 1

## Overview
This project is a responsive personal portfolio website developed using HTML, CSS, and JavaScript. The goal of the website is to present personal information, selected academic projects, and a contact form as the foundation for a larger professional portfolio.

## Implemented Features

### 1. Profile Section
The profile section introduces the student using a photo, name, role, short biography, and quick links. This section is designed as a side card that remains visually important across the page layout.

### 2. Projects Section
The Projects section presents three academic projects. Each project card includes:
- a project image
- a project title
- a short description
- technology tags

This section was built using structured HTML blocks and styled with CSS to keep a consistent card-based appearance.

### 3. Contact Form
The contact form includes three required fields:
- Name
- Email
- Message

JavaScript validates user input before submission. If the input is invalid, an error message appears below the related field. If the input is valid, a success message is shown. The form is front-end only and does not connect to a backend service.

### 4. Theme Toggle
A dark/light theme toggle was implemented using JavaScript and CSS custom properties. When the user clicks the toggle button, the page theme changes and the selected preference is stored in `localStorage`, which keeps the preference after refreshing the page.

### 5. Greeting Message
A time-based greeting is displayed on the profile image card. JavaScript reads the current local time and updates the text to show:
- Good morning
- Good afternoon
- Good evening

### 6. Responsive Navigation
The portfolio includes a desktop navigation bar and a responsive mobile menu. On smaller screens, a Menu button appears and toggles the navigation links using JavaScript.

### 7. Back to Top Anchor
A working back-to-top link was implemented in the footer. A dedicated anchor target was added at the top of the page to ensure the button works correctly without unresolved HTML anchors.

## File Structure
- `index.html`: main page structure
- `css/styles.css`: layout, theme, spacing, responsive rules, and visual styling
- `js/script.js`: theme toggle, greeting message, mobile menu, footer year, and form validation
- `assets/images/`: profile and project images
- `docs/`: supporting documentation files

## Responsive Design
The website was designed to work across desktop, tablet, and mobile screens. Media queries were used to:
- change the layout from two columns to one column on smaller screens
- collapse the navigation into a mobile menu
- resize cards and content blocks for better readability

## How to Run the Project
1. Download or clone the repository.
2. Open the project folder in VS Code.
3. Open `index.html` directly in the browser, or use Live Server.

## Testing
The website was tested by:
- resizing the browser window
- checking mobile layout in developer tools
- testing the theme toggle
- testing form validation messages
- testing the mobile menu
- testing section anchors and the back-to-top link