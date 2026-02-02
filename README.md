# Taskflow

A lightweight task manager that runs entirely in your browser. No server, no account, no install — your data stays in localStorage on your device.

**Try it now:** [klor.github.io/taskflow](https://klor.github.io/taskflow/)

## Features

- **Priorities** — Four levels (1–4) to rank task importance
- **Tags** — Create and assign multiple tags for categorization
- **Contacts & organizations** — Delegate tasks with `@mention` syntax
- **Recurring tasks** — Daily, weekly, or monthly recurrence with optional end dates
- **Due dates** — Track deadlines with overdue indicators
- **Filters** — Filter by status, tag, assignee, or delegation; click any badge to filter instantly
- **Search** — Full-text search on task titles
- **Sorting** — Automatic sort by priority then due date
- **Table / list view** — Switch between display formats
- **Undo** — 5-second undo window after completing a task
- **Dark mode** — Toggle between light and dark themes
- **Compact layout** — Adjustable display density
- **Hash-based routing** — Browser back/forward navigation between pages

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| `n` | Focus new task input |
| `/` | Focus search |
| `↑` `↓` | Navigate tasks |
| `Enter` | Edit selected task |
| `1` `2` `3` | Set priority of selected task |
| `Esc` | Close modal / return to tasks |

When creating a task, use inline syntax: `#tag` to add a tag, `@name` to assign, `!1`–`!3` to set priority, prefix with `x` to mark done immediately.

## Getting started

Use it online at [klor.github.io/taskflow](https://klor.github.io/taskflow/) — or download `taskflow.html` and open it locally. Either way, data is stored in your browser's localStorage. Nothing leaves your device.

## License

[MIT](LICENSE)
