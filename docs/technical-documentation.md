# Technical Documentation — Assignment 3

## Project Overview
This project is a responsive and interactive portfolio website developed using HTML, CSS, and JavaScript. It extends previous assignments by introducing advanced functionality such as API integration, state management, project filtering and sorting, and improved validation logic.

## Implemented Features

### 1. GitHub API Integration
The website connects to the GitHub API and fetches public repositories dynamically based on the username entered by the user. The section shows:
- repository name
- description
- primary language
- star count
- last updated date

The feature also includes:
- loading message
- no results message
- error handling if the request fails

### 2. Project Filtering and Sorting
A local JavaScript project array is used to render the Projects section dynamically. Users can:
- filter projects by category
- sort projects by year or alphabetically

This demonstrates multi-step logic and dynamic rendering.

### 3. Visitor Name State
The website allows a visitor to enter a name and save it. The value is stored in `localStorage` and shown again after refreshing the page. A clear button removes the stored name.

### 4. Theme Toggle
The dark/light theme is managed using CSS custom properties and JavaScript. The chosen theme is stored in `localStorage`.

### 5. Greeting Message
A time-based greeting is shown depending on the current local time.

### 6. Timer
The site includes a timer that counts how many seconds the visitor has been on the page.

### 7. Contact Form Validation
The contact form checks:
- minimum length for name
- valid email format
- minimum length for message
- checkbox confirmation

Error messages appear below each invalid field, and a success message appears after valid submission.

### 8. Responsive Navigation
The site includes desktop navigation and a mobile menu button that toggles the navigation links on smaller screens.

### 9. User Guidance
A dedicated guide section was added to improve user experience. It gives step-by-step instructions explaining how to navigate the site, use the projects section, load GitHub repositories, and interact with the contact form.

## File Structure
- `index.html`: main page structure
- `css/styles.css`: all styling, layout, and responsive behavior
- `js/script.js`: all interactivity and dynamic logic
- `assets/images/`: image files
- `docs/`: documentation files

## Performance Notes
- lightweight structure
- no heavy frameworks
- simple and efficient DOM updates
- minimal API requests
- responsive layout without external libraries

## Testing
The site was tested for:
- navigation links
- theme toggle persistence
- visitor name persistence
- project filtering and sorting
- GitHub API loading and errors
- mobile menu
- contact form validation
- responsiveness
- back-to-top link