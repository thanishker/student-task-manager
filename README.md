# SmartTask — Student Task Manager

A responsive, browser-based task manager for organizing assignments, exams, projects, and personal to-dos.

> **Project status:** This repository is an adapted starter project based on [SmartTask — Student Task & Productivity Dashboard](https://github.com/prateek8756/SmartTask-Student-Task-Productivity-Dashboard). The original source and its author are credited here. I am using it as a learning project and will document my own changes as I understand and extend the code.

## Features

- Dashboard with task totals, due-today tasks, category breakdown, and upcoming tasks
- Create, edit, view, complete, and delete tasks
- Search tasks by title or description
- Filter by status, category, and priority
- Sort by due date, priority, or creation date
- Save tasks and profile preferences in browser `localStorage`
- Responsive layout with dark/light theme support

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage`

This is a **frontend-only** application. It does not currently have a backend, database, user authentication, or cross-device synchronisation. Data is saved only in the browser and device where the app is used.

## Project files

All files are in the repository root:

| File | Purpose |
| --- | --- |
| `index.html` | Landing page |
| `dashboard.html` / `dashboard.js` | Dashboard interface and rendering |
| `tasks.html` / `task-list.js` | Task list, search, filters, and sorting |
| `task-form.html` / `task-form.js` | Add and edit tasks |
| `task-details.html` / `task-details.js` | Individual task details and actions |
| `profile.html` / `profile.js` | Local profile and preferences |
| `tasks.js` | Task data, CRUD operations, filtering, and statistics |
| `app.js` | Shared navigation, theme, toast, and confirmation UI |
| `validation.js` | Task form validation |
| `landing.js` | Landing page sample-task preview |
| `style.css` | Application styles and responsive layout |

## Run locally on macOS

No package installation or build step is required.

1. Download this repository as a ZIP and extract it, or open the project folder you already downloaded.
2. Open **Terminal**.
3. Type `cd ` (with a space after it), drag the extracted project folder from Finder into Terminal, then press **Return**.
4. Run:

   ```bash
   python3 -m http.server 8000
   ```

5. Open [http://localhost:8000](http://localhost:8000) in your browser.
6. Start at the landing page, then try the Dashboard, Tasks, Add task, and Profile pages.

To stop the local server, return to Terminal and press **Control + C**.

You can also open `index.html` directly in a browser, but using the local server is the recommended way to test the pages together.

## Try the app

1. Open **Add task** and enter a title, category, priority, due date, and status.
2. Save the task and confirm it appears in the task list and dashboard.
3. Edit a task, mark it completed, and delete a test task.
4. Refresh the page and confirm that your tasks remain saved in the same browser.
5. Try search, filters, sorting, and the theme toggle.

The app creates sample tasks on first run. Use the reset option in Profile only when you want to clear your browser's saved task data and restore the sample data.

## Attribution

Starter project: [prateek8756/SmartTask-Student-Task-Productivity-Dashboard](https://github.com/prateek8756/SmartTask-Student-Task-Productivity-Dashboard).

Please retain the original project's copyright and license notices. Any additional changes made in this repository should be described accurately in future commits.
