# React Todo List

This project is a dynamic Todo List application built with React. It allows users to categorize tasks under custom headings, making it easier to manage different areas of life or work.

## Features

*   **Add Custom Headings**: Create separate cards for different categories of tasks (e.g., "Work", "Groceries").
*   **Add Tasks**: Add multiple list items under each specific heading.
*   **Delete Categories**: Remove a heading and all its associated tasks with a single click.
*   **Independent Inputs**: Each section maintains its own input state for adding new items.

## Component Structure

The main logic resides in `TodoList.jsx`:

*   `todos`: State array storing objects with `heading` and `lists`.
*   `headingInput`: State for the main input field to create new headings.
*   `listInputs`: State object tracking input values for adding items to specific headings.

## Usage

1.  Enter a name in the "Enter heading" box and click **Add Heading**.
2.  In the newly created card, type a task in the "Add List" box.
3.  Click **Add List** to save the task under that heading.
4.  Click **Delete Heading** to remove a card.

## Installation

1.  Clone the repository.
2.  Navigate to the project directory:
    ```bash
    cd todo_list
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Start the application:
    ```bash
    npm start
    ```