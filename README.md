# 📋 DSA Tracker

This web application helps you keep track of DSA (Data Structures and Algorithms) problems you are working on. You can add new problems, view them in a table, and delete them as needed.

## 🌟 Project Overview

The DSA Tracker project involves:

1. **Adding Problems**: Enter problem details and add them to the list.
2. **Viewing Problems**: See all added problems in a table.
3. **Deleting Problems**: Remove problems from the list.

## 📂 Files

- `index.html`: Contains the HTML structure of the application.
- `style.css`: Contains JavaScript logic for updating and managing the problem list.
- `script.js`: Contains the JavaScript code to handle user interactions and manage local storage.

## 🛠️ Usage

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/dsa-tracker.git
cd dsa-tracker
```

### 2. Open `index.html` in your preferred web browser.

### 3. Interact with the application:

- **Add Problems**: Fill in the form with the problem's title, topic, and description, then click "Add to list."
- **View Problems**: The added problems will be displayed in a table.
- **Delete Problems**: Click the "Delete" button next to any problem to remove it from the list.

## 🌐 Features

- **Form to Add Problems**: Input fields for problem title, topic, and description.
- **Dropdown for Difficulty Level**: Select the difficulty level of the problem.
- **Table of Problems**: Displays all added problems with options to delete.
- **Local Storage**: Problems are stored in the browser's local storage to persist between page reloads.

## 🗂️ File Structure

```
dsa-tracker/
│
├── index.html
├── style.css
└── script.js
```

### `index.html`

Sets up the HTML structure for the tracker, including navigation, form inputs, and problem table.

### `style.css`

Contains JavaScript code for managing local storage and updating the problem list.

### `script.js`

Includes functions for adding problems, updating the table, and deleting entries:
- `Update()`: Refreshes the problem table from local storage.
- `getAndUpdate()`: Adds a new problem to local storage and updates the table.
- `deleted(itemIndex)`: Deletes a problem at the specified index.
- `clearAll()`: Clears all problems from local storage (currently commented out).

## 💾 Local Storage

The application uses the browser's local storage to save problem data. The problems are stored in an array and managed using the key `itemsJson`.
