 focus-blocks/
├── public/
│   └── index.html
├── src/
│   └── App.jsx
│   └── index.js
├── package.json
├── .gitignore
├── README.md{
  "name": "focus-blocks",
  "version": "1.0.0",
  "description": "Focus Blocks - Pomodoro productivity timer",
  "main": "src/index.js",
  "scripts": {
    "start": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "vite": "^4.0.0"
  }
}
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Focus Blocks</title>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/index.js"></script>
  </body>
</html>
import React from "react";
import ReactDOM from "react-dom/client";
import FocusBlocks from "./App";
import "./index.css";

ReactDOM.createRoot(document.getElementById("root")).render(
  <React.StrictMode>
    <FocusBlocks />
  </React.StrictMode>
  body {
  margin: 0;
  font-family: system-ui, sans-serif;
  background-color: #f3f4f6;
}
);
