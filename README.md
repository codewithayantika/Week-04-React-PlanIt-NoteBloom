# PlanIt + NoteBloom 🌷

A combined, responsive React mini-project featuring two independent productivity tools:

- **PlanIt** — task management with add/edit/delete, completion, categories, priority, due dates, searching, sorting and progress tracking.
- **NoteBloom** — notes with create/edit/delete, search, categories, pastel note colors, pinning and archiving.

## Requirements
- Node.js 18+ (recommended)
- npm

## Run locally
1. Extract the ZIP.
2. Open the `planit-notebloom` folder in VS Code.
3. Open Terminal in VS Code.
4. Install dependencies:
   ```bash
   npm install
   ```
5. Start the local development server:
   ```bash
   npm run dev
   ```
6. Open the localhost URL printed in the terminal (usually `http://localhost:5173`).

## Build check
```bash
npm run build
```

## Features
### PlanIt
- Create tasks with title, description, category, priority and optional due date
- Edit and delete tasks
- Mark tasks complete/incomplete
- Filter by category
- Search task title, details and category
- Sort by newest, due date, or priority
- Completion progress indicator

### NoteBloom
- Create, edit and delete notes
- Search note title, body and category
- Categories (Thoughts, Study, Personal, Ideas, Lists)
- Five pastel note backgrounds
- Pin notes to the top
- Archive/unarchive notes

### Shared
- Dashboard and navigation
- Responsive mobile/desktop layout
- Browser localStorage persistence (data stays in the same browser on refresh; it is not synced across devices)
- Decorative floral doodles are inline SVG/CSS, so no external image assets are required

## Storage
Data is saved in browser localStorage under `planit_tasks_v1` and `notebloom_notes_v1`. Clearing browser storage will clear the app data.


## Deployment
The app is a static Vite site and can be deployed to GitHub Pages, Netlify, Vercel or similar. For GitHub Pages, configure the base path if deploying from a repository subpath; otherwise use a hosting platform that supports Vite builds with minimal configuration.


## Folder structure
```
planit-notebloom/
├── index.html
├── package.json
├── vite.config.js
├── README.md
└── src/
    ├── main.jsx
    └── styles.css
```
