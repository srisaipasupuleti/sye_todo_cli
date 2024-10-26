# SYE ToDo CLI Application

A simple and efficient command-line interface (CLI) tool for managing a personal to-do list, allowing you to add, view, move, and remove tasks with ease.

## Installation

First, install the package using `pip`:
```bash
pip install syetodocliapp
```

Once installed, you can use the `todo` command to interact with the tool.

## Usage

The `todo` command offers several subcommands, each for different operations on your to-do list. Here are the commands and options available:

### 1. Add a Task

Add a new task to the to-do list.
```bash
todo add "<task_description>"
```

**Example:**
```bash
todo add "Complete project documentation"
```

### 2. List Tasks

Display tasks in your to-do list, optionally filtered by their status.

```bash
todo list [OPTIONS]
```

#### Options:
- `-s`, `--status`: Filter tasks by status. Acceptable values are:
  - `new`
  - `inprogress`
  - `done`
  - `all` (default)

**Example:**
```bash
todo list
todo list -s inprogress
```

### 3. Move a Task

Change the status of a specific task by its index in the list.

```bash
todo move <index> [OPTIONS]
```

#### Arguments:
- `<index>`: The position of the task in the to-do list.

#### Options:
- `-s`, `--to-status`: Specify the target status for the task.
  - Acceptable values: `new`, `inprogress`, `done`

**Example:**
```bash
todo move 0 -s done
```

### 4. Remove a Task

Remove a task from the to-do list by specifying its index.

```bash
todo remove <index>
```

**Example:**
```bash
todo remove 1
```

## Task Status Symbols

Tasks in the list are displayed with the following progress symbols to indicate their status:
- `□` : New
- `▣` : In Progress
- `■` : Done


---

With this CLI tool, managing your tasks is as easy as typing a command. Enjoy using ToDo CLI!
```