# Far-Away

Far-Away is a React-based travel packing list application. It allows users to add, delete, and manage items they need to pack for their trips. The application also provides sorting and filtering options to help users organize their packing list efficiently.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add items to the packing list with quantity and description.
- Mark items as packed/unpacked.
- Delete items from the list.
- Sort items by input order, description, or packed status.
- Clear the entire packing list.
- Responsive design with a user-friendly interface.

## Installation

To get started with the project, follow these steps:

1. Clone the repository:
   sh
   git clone https://github.com/your-username/Far-Away.git
   cd Far-Away
2. Install the dependencies:
   npm install
   3.Start the development server:
   npm run dev
   4.Open your browser and navigate to http://localhost:3000 to see the application in action.

## Usage

Adding Items
1.Enter the item description in the input field.
2.Select the quantity from the dropdown.
3.Click the "Add" button to add the item to the packing list.
Managing Items
1.To mark an item as packed/unpacked, click the checkbox next to the item.
2.To delete an item, click the ❌ button next to the item.
3.To sort items, select the desired sorting option from the dropdown menu.
4.To clear the entire list, click the "Clear list" button.

## Project Structure

travel-list/
├── .gitignore
├── [index.html](http://_vscodecontentref_/1)
├── [package.json](http://_vscodecontentref_/2)
├── public/
├── [README.md](http://_vscodecontentref_/3)
├── src/
│ ├── [App.jsx](http://_vscodecontentref_/4)
│ ├── [Form.jsx](http://_vscodecontentref_/5)
│ ├── [index.css](http://_vscodecontentref_/6)
│ ├── [Item.jsx](http://_vscodecontentref_/7)
│ ├── [Logo.jsx](http://_vscodecontentref_/8)
│ ├── [main.jsx](http://_vscodecontentref_/9)
│ ├── [PackingList.jsx](http://_vscodecontentref_/10)
│ ├── [Stats.jsx](http://_vscodecontentref_/11)
├── [vite.config.js](http://_vscodecontentref_/12)

-src/: Contains all the source code for the application.
-App.jsx: Main component that renders the entire application.
-Form.jsx: Component for adding new items to the packing list.
-Item.jsx: Component for displaying individual items in the list.
-Logo.jsx: Component for displaying the application logo.
-PackingList.jsx: Component for displaying and managing the packing list.
-Stats.jsx: Component for displaying statistics about the packing list.
-index.css: Contains the styles for the application.
-main.jsx: Entry point for the React application.
-vite.config.js: Configuration file for Vite.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

1.Fork the repository.
2.Create a new branch (git checkout -b feature-branch).
3.Make your changes.
4.Commit your changes (git commit -m 'Add some feature').
5.Push to the branch (git push origin feature-branch).
6.Open a pull request.
