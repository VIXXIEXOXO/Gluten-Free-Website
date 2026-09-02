# Glutena

Glutena is a gluten-free baking recipe website designed to help users discover, filter, and save gluten-free recipes while managing practical baking helpers such as a timer, calculator, notes, and unit conversion tools.

Live demo: https://brightform-studios.github.io/Glutena/

## Overview

This project was developed as a web application for gluten-free baking enthusiasts. It combines recipe discovery with useful everyday baking tools in one clean interface, making it easier to browse recipes by category and taste while supporting the planning and execution of gluten-free baking tasks.

## Features

- Search and browse gluten-free recipes
- Filter recipes by category, including bread, cake, cookies, muffins, pancakes, and more
- Filter by taste profile such as sweet, salty, and vegan
- Responsive and mobile-friendly layout
- Built-in baking tools:
  - recipe timer
  - calculator
  - notes section
  - measurement converter
- User account support with registration and login
- Personalized profile customization with profile image, banner color, and display name
- Firebase-powered backend for authentication and profile storage

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Firebase Authentication and Firestore
- GitHub Pages deployment

## Project Structure

```text
Gluten-Free-Website/
├── index.html              # Main application structure and UI
├── styles.css              # Styling and responsive design
├── firebase-config.js      # Firebase configuration
├── icon.png                # App icon
├── pattern.png             # Background texture asset
├── README.md               # Project documentation
└── .git/                   # Git metadata
```

## Getting Started

### Prerequisites

- A modern web browser
- A text editor or IDE such as VS Code
- A Firebase project (if you want to connect your own backend)

### Local Setup

1. Clone the repository:

```bash
git clone https://github.com/brightform-studios/Glutena.git
```

2. Navigate to the project folder:

```bash
cd Gluten-Free-Website
```

3. Open `index.html` in a browser, or serve the project locally with a simple HTTP server if preferred.

Example with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Firebase Configuration

The app uses Firebase for authentication and user profile data. Before using the project in a production environment, update the Firebase configuration in `firebase-config.js` with your own project credentials.

```javascript
var firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};
```

## Usage

- Open the website in a browser
- Browse or search for recipes
- Filter by category or taste preference
- Use the side menu to access the timer, calculator, converter, notes, and profile tools
- Register or log in to save a personalized profile

## Deployment

This project is configured for static hosting and is published via GitHub Pages. To deploy your own version:

1. Push the project to a GitHub repository
2. Enable GitHub Pages in the repository settings
3. Select the main branch or the appropriate publishing source
4. Use the generated GitHub Pages URL

## License

This project is intended for educational and portfolio purposes. Please check the repository license status before commercial reuse.

## Acknowledgements

This project was created as part of a web and app development course and reflects a practical recipe-focused web application built for gluten-free baking use cases.

## Contact

For questions or collaboration opportunities, please contact the project maintainer or repository owner.
