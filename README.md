# ✅ To-Do List App

A simple, lightweight to-do list that runs in the browser. Add tasks, tick them off, delete them, and your list is still there when you come back.

## Features

- **Add tasks:** type a task and add it to the list (empty tasks are blocked with a message)
- **Mark as done:** click a task to toggle it as completed
- **Delete tasks:** click the × next to a task to remove it
- **Saved automatically:** the list is stored in the browser's `localStorage`, so it survives page refreshes

## Tech stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

Vanilla HTML, CSS and JavaScript, with no frameworks or libraries.

## How it works

- `app.js` creates a list item for each task and handles clicks with a single event listener on the list (event delegation).
- After every change, the list is saved to `localStorage`; on page load it is restored from there.

## Run locally

```bash
git clone https://github.com/Shweta173/todo-list-app.git
cd todo-list-app
```

Then open `index.html` in your browser. No install or build step needed.

## Project structure

```
├── index.html   # page layout
├── style.css    # styling
└── app.js       # add, complete, delete and save tasks
```

## Author

**Shweta Kamble** · [LinkedIn](https://www.linkedin.com/in/shweta-kamble-dev) · [GitHub](https://github.com/Shweta173)
