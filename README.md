# Keeper App

A minimal notes app built with React. Add notes with a title and content, view them as cards, and delete the ones you no longer need.

## Features

- Add a note with a title and content
- View all notes in a card layout
- Delete individual notes

## Tech Stack

- React
- CSS (custom, no framework)
- Google Fonts (Montserrat, McLaren)

## Project Structure

```
├── public/
│   ├── index.html
│   └── styles.css
├── src/
│   ├── components/
│   │   ├── App.jsx
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   ├── CreateArea.jsx
│   │   └── Note.jsx
│   └── index.js
```

## Getting Started

1. Clone the repo
   ```bash
   git clone <repo-url>
   cd keeper
   ```
2. Install dependencies
   ```bash
   npm install
   ```
3. Start the development server
   ```bash
   npm start
   ```

## Notes

- State is held in memory only — notes are cleared on page refresh (no backend or local storage persistence).
