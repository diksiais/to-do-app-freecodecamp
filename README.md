# 📝 Simple Task Manager

A lightweight task management app built with **HTML, CSS, and JavaScript** — no backend required.  
It allows you to **add, edit, and delete tasks**, and it remembers your tasks in your browser using `localStorage`.

## ✨ Features

- **Add new tasks** with title, date, and description.
- **Edit existing tasks** without losing your data.
- **Delete tasks** instantly.
- **Local storage persistence** — your tasks stay even after refreshing or closing the browser.
- **Unsaved changes warning** — a confirmation dialog appears if you try to close the form with unsaved edits.
- **Clean UI** with simple toggling between form and task list.

## 🛠 Project Structure

```
.
├── index.html         # Main HTML page
├── style.css          # App styles
├── script.js          # JavaScript logic
└── README.md          # Project documentation
```

## 📂 How It Works

- **Add Task**  
  Fill in the title (required), date, and description, then click **Add Task**.  
  The task will appear at the top of the list.

- **Edit Task**  
  Click **Edit** on any task. The form will open with existing data.  
  Make your changes and click **Update Task**.

- **Delete Task**  
  Click **Delete** to remove the task instantly.

- **Close Form with Unsaved Changes**  
  If the form has unsaved input, you’ll see a confirmation dialog before closing.

## 💾 Data Storage

This app uses `localStorage` to store tasks in your browser.  
Data is saved as JSON under the key `"data"`. Clearing your browser storage will remove all tasks.

## 🔮 Possible Improvements

- Add task status (e.g., Completed / Pending)
- Search or filter tasks
- Sort by date
- Sync with a backend API for multi-device use

## 📜 Source

Freecodecamp course
