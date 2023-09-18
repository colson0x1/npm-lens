# NPM Lens

NPM Lens is a web application built with React, Redux, and TypeScript that allows you to search for NPM packages and list the matching ones. This README provides an overview of the project, installation instructions, and usage guidelines.

![npm lens - loading state](https://i.imgur.com/RCLFlqp.png)

## Table of Contents
- [NPM Lens](#npm-lens)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [Screenshots](#screenshots)
    - [npm lens - main](#npm-lens---main)
    - [npm lens - loading state](#npm-lens---loading-state)
    - [npm lens - response data](#npm-lens---response-data)

## Features
- Search for NPM packages by name.
- Display a list of matching packages.
- Handle loading and error states gracefully.
- Built with React, Redux, and TypeScript for a robust and type-safe codebase.

## Installation
To run NPM Lens locally on your machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/colson0x1/npm-lens.git
   ```

2. Change your working directory to the project folder:

   ```bash
   cd npm-lens
   ```

3. Install the project dependencies using npm:

   ```bash
   npm install
   ```

## Usage
Once you have installed the project, you can run it locally:

```bash
npm start
```

This command will start the development server, and you can access the application in your web browser at `http://localhost:3000`.

To search for NPM packages:

1. Enter a package name in the input field.
2. Click the "Search" button.
3. View the list of matching packages.

## Project Structure
The project is organized into several directories and files:

- `src/components`: Contains React components, including the main `App` component and `RepositoriesList` component.
- `src/hooks`: Custom React hooks used in the application, such as `useActions` and `useTypedSelector`.
- `src/state`: Redux-related files, including action creators, action types, reducers, and the Redux store configuration.
- `src/index.ts`: The entry point of the application where React is initialized.
- `package.json`: Contains project metadata and dependencies.
- `README.md`: The README you are currently reading.

## Screenshots
### npm lens - main
![npm lens - main](https://i.imgur.com/xzIg85E.png)

### npm lens - loading state
![npm lens - loading state](https://i.imgur.com/RCLFlqp.png)

### npm lens - response data
![npm lens - response data](https://i.imgur.com/enq7lVr.png)