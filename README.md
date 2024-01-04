# Task Manager | React + Node.js

Task manager is an app developed as a web application in order to manage your day-today tasks.
App is developed using,
#### Frontend: React + Vite + TypeScript
#### Backend: Node.js
#### Authentication: Firebase Authentication with Google Sign-In

## Table of Contents

- [Overview of technologies used](#overview-of-technologies-used)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Copyright](#copyright)

## Overview of technologies used

### Frontend:

- React: TypeScript library for building user interfaces.
- Vite: TypeScript bundler for building modern web applications.
- Firebase: Google's platform for authentication, database, and other functionalities.
- TypeScript: Programming language for frontend development.
- firebase.json: Configuration file for Firebase integration.
- 404.html: Custom error page for non-existent routes.
- node_modules: Directory for frontend dependencies.
- .eslintrc.cjs: ESLint config file for code quality checks.
- tsconfig.json & tsconfig.node.json: TypeScript configuration files for type safety.
- vite.config.ts: Vite configuration file for bundling and development settings.


### Backend:

- [Node.js](https://nodejs.org/) - JavaScript runtime for server-side development.
- [Express.js](https://expressjs.com/) - Web application framework for Node.js.
- [MySQL](https://www.mysql.com/) - Relational database management system.
- [mysql2](https://github.com/mysqljs/mysql2) - MySQL library for Node.js.
- [TypeScript](https://www.typescriptlang.org/) - Superset of JavaScript with static typing.
- [Express-serve-static-core](https://github.com/DefinitelyTyped/express) - TypeScript types for Express.js.


### Dependencies:

- "dependencies": {
    - "cors": "^2.8.5",
    - "express": "^4.18.2",
    - "mysql2": "^3.6.5"
  },
- "devDependencies": {
    - "@types/cors": "^2.8.17",
    - "@types/express": "^4.17.21",
    - "@types/node": "^20.10.6"
  }

## Installation


```bash
# Clone the repository
git clone https://github.com/IsuruWeerakkodi/task-manager-react-node.js.git

# Navigate to the frontend directory
cd front-end-react

# Install frontend dependencies
npm install
npm run dev

# Navigate to the backend directory
cd ../api-node.js

#Ensure you have the following installed on your machine:
#- [Node.js](https://nodejs.org/) 
#- [npm](https://www.npmjs.com/)
#- [MySQL](https://www.mysql.com/) (Make sure MySQL server is running)

npm run build
npm start

```

## Contributing
Before you start contributing, please read the following:

- Fork the repository: Create your own fork of the [project name] repository on GitHub. This allows you to work on your own copy of the code without affecting the main project.
- Set up your development environment: Install the necessary tools and dependencies for working on the project.
- Review the coding conventions: Follow the project's coding conventions to ensure consistency and maintainability of the codebase.

#### Submitting a Pull Request
Once you have made your changes, you can submit a pull request to the main repository. Please follow these guidelines:

- Create a descriptive pull request title and message: Briefly explain what your pull request does and why it is important.
- Test your changes: Ensure that your changes are properly tested and do not break existing functionality.
- Follow the pull request template: If there is a pull request template, please use it to fill out your pull request information.

## License

This project is licensed under the MIT License - [click here](LICENSE.txt) for more details.

## Copyright
Copyright © 2024 Isuru Weerakkodi - All rights reserved.
