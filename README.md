# Quick Notes

A lightweight browser-based note-taking app built with vanilla JavaScript, HTML, and CSS.

## Features

- Create, edit, and delete notes
- Persist notes in the browser with `localStorage`
- Toggle between light and dark themes
- Responsive note grid layout
- No build tools, dependencies, or backend required

## Getting Started

1. Clone or download this project.
2. Open `index.html` in a modern web browser.
3. Select **+ Add Note** to create your first note.

For the most reliable local development experience, serve the project with any static file server and open the provided local URL.

## Project Structure

```text
.
├── index.html          # Application markup
├── scripts/
│   └── main.js         # Note management and theme logic
└── styles/
    └── main.css        # Layout and visual styles
```

## Data Storage

Notes are stored locally in the browser under the `quickNotes` key. The selected theme is stored under the `theme` key. Data is specific to the browser and device where the app is used; clearing browser storage removes the saved notes and theme preference.

## Development

This project uses plain web technologies, so no installation step is needed. Edit the source files and refresh the browser to see changes.