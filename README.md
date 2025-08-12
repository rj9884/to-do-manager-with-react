
# TodoManager

A simple Todo Manager application built with React and Vite. This app allows users to add, view, and manage their todo items efficiently.

## Live Website
You can try the app live here: [TodoManager Live](<your-live-link-here>)

## Demo
![TodoManager Demo](<screenshot-url-or-path>)

## Screenshots
![Home Page](/src/assets/home.png)
![Add Todo](/src/assets/addToDo.png)
![Edit Todo](/src/assets/editToDo.png)
![Completed Todo](/src/assets/completedToDo.png)

## Features
- Add new todos
- Mark todos as completed
- Remove todos
- Context-based state management
- Modern React with hooks and context API

## Project Structure
```
TodoManager/
├── public/
│   └── todoIcon.png
├── src/
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── components/
│   │   ├── TodoForm.jsx
│   │   └── TodoItem.jsx
│   └── context/
│       ├── Index.js
│       └── TodoContext.js
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
└── README.md
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm

### Installation
1. Clone the repository:
	```powershell
	git clone to-do-manager-with-react
	cd to-do-manager-with-react
	```
2. Install dependencies:
	```powershell
	npm install react react-dom tailwindcss
	```

### Running the App
Start the development server:
```powershell
npm run dev
```

## Usage
- Use the input field to add new todos.
- Click on a todo to mark it as completed.
- Click the delete icon to remove a todo.

## Technologies Used
- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)

## License
This project is licensed under the MIT License.
