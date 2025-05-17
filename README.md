# React Todo Example

This is a simple React todo app that runs entirely in your browser.

## Getting Started

1. Download or clone this repository.
2. Open `index.html` directly in a modern browser **or** run a small local server:
  ```
  npx serve
  # or
  python3 -m http.server 8000
  ```
  Then visit the shown URL (e.g. http://localhost:8000).

Open `index.html` in your browser to run the app. A UUID is saved in `localStorage` to keep user-specific data. Todo items are stored in IndexedDB. You can drag and drop images into the content field. The interface uses Tailwind CSS for styling so no build step is required.
