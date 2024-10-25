# SYE Todo CLI App

`syetodocliapp` is a command-line interface (CLI) application for managing your tasks. With this tool, you can easily add, list, and remove tasks directly from your terminal.

## Features

- **Add Tasks**: Quickly add new tasks to your list.
- **List Tasks**: View all your tasks along with their statuses.
- **Remove Tasks**: Easily remove tasks when they are no longer needed.

## Installation

You can install the `syetodocliapp` package from the Python Package Index (PyPI). Use the following command:

```bash
pip install syetodocliapp
```

## Usage

After installation, you can use the `todo` command to interact with the application. The basic syntax is:

```bash
todo <command> [options]
```

## Commands

### 1. Add a Task

To add a new task to your to-do list, use the `add` command followed by the task description.

```bash
todo add <task>
```

**Example:**
```bash
todo add "Buy groceries"
```

### 2. List Tasks

To list all tasks along with their current statuses, use the `list` command.

```bash
todo list
```

### 3. Remove a Task

To remove a task from your list, use the `remove` command followed by the index of the task.

```bash
todo remove <index>
```

**Example:**
```bash
todo remove 0
```

## Task Status Representation

The application uses the following symbols to represent task statuses:

- New: `□` 
- In Progress: `▣` 
- Done: `■` 

## Contributing

Contributions are welcome! If you'd like to improve this project, please submit a pull request or open an issue on the repository.

## Author

**Srisai Pasupuleti**  
Email: [srisaichiyan24@gmail.com](mailto:srisaichiyan24@gmail.com)
