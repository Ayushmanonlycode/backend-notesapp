# Notes App

A simple Node.js and Express app for creating and viewing text-based tasks/notes. Uses EJS for templating and Tailwind CSS for styling.

## Features

- Create new tasks with a title and details
- View a list of all tasks
- Read individual tasks
- Styled with Tailwind CSS

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```
   git clone <your-repo-url>
   cd notes
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the server:
   ```
   node index.js
   ```

4. Open your browser and go to [http://localhost:3000](http://localhost:3000)

## Project Structure

```
notes/
├── files/                # Saved tasks (created at runtime)
├── public/
│   └── views/
│       ├── index.ejs     # Main page
│       └── show.ejs      # Task details page
├── index.js              # Main server file
├── package.json
```

## Usage

- Fill in the form to create a new task.
- Click "Read more!" to view task details.
- Click "Go back" to return to the main page.
