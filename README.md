# User Registration App

## Overview
This project is a simple user registration application built with React. It allows users to input their name and age, and add this information to a list. Users can also delete entries from the list. This project demonstrates the use of React hooks, including `useState` and `useRef`, as well as basic list rendering and event handling.

## Features
- **User Registration**: Users can add their name and age to the list.
- **Delete User**: Users can delete any entry from the list.
- **Unique IDs**: Each user entry is assigned a unique ID using the `uuid` library.

## Technologies Used
- **React**: A JavaScript library for building user interfaces ⚛️.

- **Styled Components**: For component-level styling 💅.
- **UUID**: For generating unique IDs 🆔.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/user-registration-app.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd user-registration-app
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Start the development server**:
   ```bash
   npm start
   ```

5. Open your browser and go to `http://localhost:3000` to see the app in action.

## Project Structure
The project structure is as follows:

```
.../
├── node_modules/
├── public/
├── src/
│   ├── style.js
│   ├── App.js
│   ├── index.js
├── .gitignore
├── package.json
├── README.md
└── yarn.lock
```

### Explanation of Key Files
- **App.js**: The main component of the application. Contains the logic for adding and deleting users.
- **style.js**: Contains styled-components for styling the application.
- **index.js**: The entry point of the React application.

## How It Works
1. **Adding a User**:
   - Users enter their name and age in the input fields.
   - When the "Cadastrar" button is clicked, the `AddNewUser` function is triggered.
   - This function adds a new user object to the `users` state array, with a unique ID generated by `uuid`.

2. **Deleting a User**:
   - Each user entry in the list has a "Deletar" button.
   - When this button is clicked, the `deleteUser` function is triggered.
   - This function filters out the user with the matching ID from the `users` state array, updating the state to reflect the deletion.

## Components
### Container
Styled component that acts as the main container for the application.

### Form
Styled component for the user input form.

### Input
Styled component for input fields (name and age).

### Button
Styled component for the "Cadastrar" button.

### ToDoList
Styled component for the list of users.

### ListItem
Styled component for each user entry in the list.

### Trash
Styled component for the delete button.

## Future Improvements
- **Form Validation**: Add validation to ensure that name and age fields are not empty and that age is a number.
- **Local Storage**: Save the user list in local storage so that it persists across page reloads.
- **Edit Functionality**: Allow users to edit existing entries.

## Conclusion
This project serves as a simple introduction to React and state management using hooks. It covers essential concepts like handling user input, managing state, and rendering lists dynamically.

Feel free to contribute to this project by forking the repository and submitting pull requests. For any issues or feature requests, please use the issue tracker on GitHub.

---

Made with ♥ by Tiago Santos :wave: [Get in touch!](https://www.linkedin.com/in/tiagosantos-dev/)
