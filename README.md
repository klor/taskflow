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

## Usage

### Adding tasks

Type a task title in the input field and press Enter (or click Add). Use shorthand syntax to set properties inline:

| Syntax | Effect |
|--------|--------|
| `#tag` | Assign a tag (creates it if new) |
| `@name` | Delegate to a contact or organization |
| `!1` `!2` `!3` | Set priority (1 = high, 3 = low) |
| `x` at start | Mark as done immediately |

**Example:** `Review proposal #projectx @john !2` creates a task titled "Review proposal", tagged *projectx*, assigned to *john*, with priority 2.

### Task list

Tasks are sorted by priority then due date. Switch between **Table** and **List** view using the toggle above the list.

**Filtering** — Click **Waiting**, **Done**, or **Delegated** to include those tasks. Click any tag or assignee badge in the list to filter by it. Use the search field to filter by title.

### Keyboard shortcuts

| Key | Action |
|-----|--------|
| `n` | Focus new task input |
| `/` | Focus search |
| `↑` `↓` | Navigate tasks |
| `Enter` | Edit selected task |
| `1` `2` `3` | Set priority of selected task |
| `Esc` | Close modal / return to tasks |

### Master data

Manage reusable data from the **Tags** nav item or the settings menu:

- **Tags** — categorize tasks (e.g. Backend, Urgent, ProjectX)
- **Contacts** — people you delegate tasks to
- **Organizations** — group contacts by company

## Demos

Pre-built demos with realistic task data for different roles. Each runs independently with its own localStorage.

**[Browse all demos →](https://klor.github.io/taskflow/demos/)**

| Demo | Persona |
|------|---------|
| [BC Consultant](https://klor.github.io/taskflow/demos/bc-consultant.html) | Business Central consultant managing SMB client implementations and support |
| [BC Solution Architect](https://klor.github.io/taskflow/demos/bc-architect.html) | Business Central solution architect across manufacturing clients |
| [Development Manager](https://klor.github.io/taskflow/demos/dev-manager.html) | Dev manager leading 18 developers on a B2B SaaS product |
| [Product Manager](https://klor.github.io/taskflow/demos/product-manager.html) | Product manager on a B2B SaaS platform for manufacturing |
| [Project Manager](https://klor.github.io/taskflow/demos/project-manager.html) | Project manager across multiple client engagements |
| [Sales Manager](https://klor.github.io/taskflow/demos/sales-manager.html) | Sales manager running a B2B SaaS sales pipeline |

## Getting started

Use it online at [klor.github.io/taskflow](https://klor.github.io/taskflow/) — or download `index.html` and open it locally. Either way, data is stored in your browser's localStorage. Nothing leaves your device.

## License

[MIT](LICENSE)
