# Todo App

A simple and elegant Todo List application built with React.

## Features

✅ **Add Todos** - Quickly add new tasks to your list
✅ **Mark Complete** - Check off completed todos
✅ **Delete Todos** - Remove tasks you no longer need
✅ **Save Progress** - Your todos are saved in the browser (LocalStorage)
✅ **Beautiful UI** - Clean, modern design with smooth animations

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rockmanlv3-stack/todo-app.git
   cd todo-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and go to `http://localhost:3000`

## How to Use

1. **Add a Todo**: Type your task in the input field and click "Add"
2. **Complete a Todo**: Click the checkbox next to a task to mark it as complete
3. **Delete a Todo**: Click "Delete" to remove a task
4. **Your todos are automatically saved** - Close the browser and come back, your todos will still be there!

## Project Structure

```
src/
├── App.jsx           # Main app component
├── App.css           # App styling
├── index.js          # Entry point
├── index.css         # Global styles
└── components/
    ├── TodoInput.jsx # Input form component
    ├── TodoList.jsx  # Todo list container
    └── TodoItem.jsx  # Individual todo item
```

## Technologies Used

- **React** - UI library
- **LocalStorage** - Data persistence
- **CSS3** - Styling and animations

## Future Features

- 📝 Edit existing todos
- 🏷️ Add categories/tags
- 🎯 Set due dates
- 🌙 Dark mode
- 📱 Mobile app version

## License

This project is open source and available under the MIT License.

## Getting Help

If you run into issues, feel free to create a GitHub issue in this repository!