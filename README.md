# Daily Task Planner Web App

A beautiful daily task planner built with **React + TypeScript + Vite**. You can add, edit, delete, complete, search, and move tasks between dates. Tasks are saved in your browser using **localStorage**, so you can run it without a backend or database.

## Features

- View tasks for any selected date
- Add a new task with title, description, date, time, priority, category, and status
- Edit existing tasks
- Delete tasks
- Mark tasks as completed or pending
- Move tasks to yesterday or tomorrow
- Search tasks
- Progress summary for each day
- Dates-with-tasks sidebar
- Local browser storage
- Responsive UI for desktop and mobile
- Change look and feel from the app:
  - Themes: Sunrise, Ocean, Forest, Midnight
  - Layouts: Cozy, Compact

## Tech Stack

- React
- TypeScript
- Vite
- CSS
- localStorage

## Requirements

Install Node.js before running this app.

Recommended version: Node.js 18 or higher.

Check your version:

```bash
node -v
npm -v
```

## How to Run Locally

1. Open terminal or command prompt.

2. Go to the project folder:

```bash
cd daily-task-planner
```

3. Install dependencies:

```bash
npm install
```

4. Start the app:

```bash
npm run dev
```

5. Open the local URL shown in terminal. It will usually be:

```text
http://localhost:5173
```

## How to Build for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Where Tasks Are Saved

Tasks are saved in the browser's localStorage. This means:

- No login is required
- No database is needed
- Tasks stay saved on the same browser and computer
- Clearing browser storage will delete saved tasks

## How to Customize UI

Inside the app, use the top-right controls:

- **Theme**: changes color style
- **Layout**: changes spacing and density

To add more themes, edit this file:

```text
src/App.css
```

Look for these classes:

```css
.theme-sunrise
.theme-ocean
.theme-forest
.theme-midnight
```

You can add your own theme by creating a new class and adding it to the dropdown in:

```text
src/App.tsx
```

## Suggested Future Improvements

- User login
- Cloud database such as MongoDB or Firebase
- Calendar month view
- Drag-and-drop task ordering
- Task reminders
- Recurring tasks
- Export tasks to PDF or CSV
