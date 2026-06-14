# My Todo App

A simple, user-friendly todo application built with **Streamlit**. This app helps you manage your tasks and increase your productivity.

## Features

- ✅ **Add Todos**: Easily add new todo items using the text input field
- ✅ **Mark Complete**: Check off completed tasks with a single click
- ✅ **Persistent Storage**: Your todos are saved to a text file automatically
- ✅ **Simple Interface**: Clean and intuitive Streamlit-based UI

## Requirements

- Python 3.7+
- Streamlit

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd my-todo-app
   ```

2. **Install dependencies**:
   ```bash
   pip install streamlit
   ```

## Usage

To run the application:

```bash
streamlit run web.py
```

The app will start on `http://localhost:8501` by default.

### How to Use

1. **Add a Todo**: Type your task in the "Add new todo..." field and press Enter
2. **Mark as Complete**: Check the checkbox next to a todo item to mark it as done
3. **Automatic Removal**: Completed items are automatically removed from the list

## Project Structure

- `web.py` - Main Streamlit application file
- `functions.py` - Core functions for managing todos (read/write operations)
- `todos.txt` - File where todos are stored

## Development

### Functions

#### `get_todos(filepath='todos.txt')`
Reads and returns a list of todo items from the specified file.

#### `write_todos(todos, filepath='todos.txt')`
Writes the todo list to the specified file.

#### `show_list(todos)`
Displays all todos in the console format.

## Future Improvements

- Deploy the todo app (as noted in todos.txt)
- Add due dates for todos
- Implement categories or tags
- Add priority levels
- Enable data persistence with a database
