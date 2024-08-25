This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

Overview
---------
This project is a frontend application that mimics the functionality of a traditional spreadsheet. Built with Next.js and styled using Tailwind CSS, the application includes core spreadsheet features, advanced functionalities, and a user-friendly interface. The project uses zustand for state management to handle the grid data efficiently.

Features
----------
Core Functionality:

Grid Rendering: Displays a grid of 1000 blank cells.
Cell Editing: Allows users to edit cell content dynamically.
Data Storage: Manages cell data in memory with persistent state.
Cell Styling: Features clear grid lines, padding, and font styles.

Advanced Features:
--------------------
Cell Formatting: Basic formatting options like text alignment and font size adjustments.

Data Validation: Restricts cells to numeric values or specific text formats.

Search and Filter: Enables quick data location within the grid.

Pagination: Implements pagination or infinite scrolling for large datasets.

Undo/Redo: Provides functionality to revert changes made to cells.

Prerequisites
Before you begin, ensure you have the following installed:

Node.js (>= 14.x)
npm 
Setup and Installation
Clone the Repository

cd spreadsheet-app
Install Dependencies

Using npm:

Copy code
npm install

Using npm:

run:
npm run dev

The application should now be running on http://localhost:3000.

Usage
Navigating the Grid: Scroll to navigate through the 1000 cells in the grid.
Editing Cells: Click on a cell to enter edit mode and type the desired content.
Formatting Cells: Use the formatting toolbar to adjust text alignment and font size.
Search and Filter: Use the search bar to locate specific data within the grid.
Pagination/Infinite Scrolling: If the dataset is large, use the pagination controls or scroll to load more data.
Undo/Redo: Use the undo and redo buttons to revert or reapply changes.
Advanced Features
Cell Formatting: Select a cell and use the formatting options to align text or change font size.
Data Validation: Cells may have validation rules that restrict input types.
Search and Filter: Enter search terms to filter visible cells by content.
Pagination: Navigate between pages of data or use infinite scrolling.
Undo/Redo: Revert or reapply recent changes with the undo/redo functionality.

Testing
----------
Run unit and integration tests using the following command:

Using npm:

bash
npm test

## Deployment

For live demo, the application is deployed on Vercel/Netlify (or the appropriate deployment platform). You can view the live application by visiting the link.

Code Quality and Best Practices
The code is organized into functional components and follows Next.js best practices.
Tailwind CSS is used for responsive and maintainable styling.
Zustand is used for state management, ensuring efficient data handling.
Documentation
Component Architecture: The application follows a component-based architecture with reusable and modular components.
State Management: Zustand manages the application state, including cell data and user interactions.
Styling: Tailwind CSS provides a clean, responsive design with customizable utility classes.
Troubleshooting
If the application is not starting, ensure all dependencies are installed and try restarting the development server.
For styling issues, check Tailwind CSS configurations and ensure they are properly set up.
Contributing
Contributions are welcome! If you’d like to contribute, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.