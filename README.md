Spotify Clone

About the project

This project is a recreation of Spotify Web, developed during Alura's Front-end Dev Immersion. It features a simple interface and a search filter linked to a fake API. The project was built using HTML, CSS, JavaScript, and React, along with JSON-Server.

Features
✅ Functional search bar: Filters registered artists and playlists based on the search input.

Project Structure
📂 public/: Stores React's predefined files and the project’s favicon.
📂 src/: Stores the subfolders "assets" and "components", along with other files.
    📂 components/: Contains the "Footer", "Main", and "Sidebar" subfolders for componentization. (Each subfolder includes its respective JS files for application structure and CSS files for styling).
    📜 script.js: Handles the logic for the search filter.
    📜 App.js: The main file, combining all components.
    📜 App.css: Dedicated styling file for resets, CSS variables, body styling, and media queries.
📜 App.test.js, index.css, index.js, reportWebVitals.js, setupTests.js, package-lock.json, package.json: Files that come with the React application by default.
📂 assets/: Stores "icons" and "playlists" subfolders.
    📂 icons/: Contains icons used in the project.
    📂 playlists/: Contains images of playlists displayed on the main page.
📜 artists.json: Stores the fake API data.

Prerequisites
🔹 A modern browser like Google Chrome, Mozilla Firefox, or Microsoft Edge.
🔹 An IDE like VSCode.
🔹 All project files correctly linked.
🔹 NodeJS and NPM installed.
🔹 Required JSON-Server version: 0.17.0 or 0.17.4.

How to Use:

1️⃣ Clone the repository or copy the files to your computer.
2️⃣ Ensure all files are in the same directory.
3️⃣ Install NodeJS and NPM via your terminal.
4️⃣ Install JSON-Server in the required version.
5️⃣ Open the IDE terminal and start JSON-Server on port 5000 using: json-server --watch artists.json --port 5000

6️⃣ Open another terminal and start the React application with:

npm start

7️⃣ Explore the project! 🎵🚀

Let me know if you need any modifications! 😊