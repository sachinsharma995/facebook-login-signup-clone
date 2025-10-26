<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/64207cab-2696-4735-8bca-e9c660264c5d" />

📘 Facebook Login Page Clone (Tailwind CSS)

🌟 Overview

This project is a clean, modern clone of the Facebook desktop login page. It is built using pure HTML for structure and Tailwind CSS for all styling, ensuring a fully responsive and utility-first approach to design.

Key Features

Utility-First Styling: All styles are applied using Tailwind CSS utility classes directly in the HTML.

Accurate Visuals: Close visual fidelity to the original Facebook login page structure, including input fields, buttons, and overall layout.

🛠️ Technology Used

HTML5: The core structure of the page.

Tailwind CSS: Used for all styling, layout (Flexbox), color palettes, and responsive design features.

🚀 Setup and Installation

Follow these steps to get a copy of the project running on your local machine.

Prerequisites

You need to have Node.js and npm installed to run the Tailwind CSS build process.

Node.js (LTS)

Local Development

Clone the Repository

git clone [YOUR_REPO_URL]
cd facebook_project_1 


Install Dependencies
Navigate to the project directory and install the necessary npm packages, which include Tailwind CSS and PostCSS.

npm install


Run the Tailwind Build Process
This command will watch your HTML file for class changes and compile the final style.css file.

npx tailwindcss -i ./src/input.css -o ./style.css --watch


(Note: Adjust the input/output paths (-i and -o) if your file structure is different from the standard setup.)

Open in Browser
Open the index.html file directly in your web browser to view the live page.

📁 Project Structure

facebook_project_1/
├── index.html              # Main HTML structure
├── style.css               # Compiled Tailwind CSS output (linked in HTML)
├── tailwind.config.js      # Tailwind configuration file
├── postcss.config.js       # PostCSS configuration
├── package.json            # Project dependencies and scripts
└── .gitignore              # Ensures node_modules and other files are ignored (Critical!)
