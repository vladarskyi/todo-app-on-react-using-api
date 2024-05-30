# Todo App on React using API

Welcome to the Todo App project! This project focusing on implementing a fully functional todo application with features such as toggling and renaming todos.

## Demo

Check out the [DEMO](https://vladarskyi.github.io/todo-app-on-react-using-api/) to see it in action!

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a standalone todo application built with React. It allows users to manage their tasks by adding, deleting, toggling, and renaming todos. The application communicates with an API to persist data and ensure a seamless user experience.

## Features

- Add new todos
- Delete existing todos
- Toggle the completed status of individual todos
- Toggle the completed status of all todos using a "toggle all" checkbox
- Edit the title of a todo on double-click
- Display loaders while waiting for API responses
- Show notifications for API errors

## Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/vladarskyi/todo-app-on-react-using-api.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-app-on-react-using-api
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

### Running the App

To run the application locally, use the following command:

   ```bash
   npm start
   ```

This will start the development server and open the application in your default web browser. You can access it at http://localhost:3000/.

## Folder Structure

The project follows a standard folder structure for better organization:

  ```graphql
todo-app-on-react-using-api/
│
├── src/                 # Source files
│   ├── api/             # Functions for interacting with the API
│   ├── components/      # Components of the app
│   ├── styles/          # SCSS stylesheets
│   ├── types/           # Typescript types
│   ├── utils/           # Helping functions
│   └── index.tsx        # Entry point of the application
│
├── .gitignore           # Git ignore file
├── package.json         # Project metadata and dependencies
├── README.md            # Project documentation
└── ...
  ```

## Contributing

Contributions are welcome!

## License

This project is licensed under the MIT License.