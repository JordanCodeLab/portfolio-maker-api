<br>

<div align="center">

  <h1 align="center">Portfolio Maker API</h1>

  <p align="center">
    <strong>is an open-source project developed in TypeScript that helps developers create and manage their portfolios.</strong>
  </p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D14.0.0-brightgreen.svg)](https://nodejs.org/)
[![TypeScript](https://badgen.net/badge/TypeScript/4.x/blue)](https://www.typescriptlang.org/)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/JordanCOdeLab/portfolio-maker-api/issues)

</div>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About](#about)
- [Contributing](#-contributing)
  - [Fork and clone your repository](#fork-and-clone-your-repository)
  - [Project Structure](#project-structure)
- [Contributors](#contributors)
- [License](#license)

## About
**Portfolio Maker API** is an open-source project that provides developers with a robust API to create and manage their portfolios. With RESTful endpoints, users can easily manage projects, skills, and experiences, facilitating a seamless portfolio creation process. The project is built with TypeScript, ensuring type safety and enhancing development efficiency.

## <a name="contributing"> Contributing

### Fork and clone your repository

1. Fork the repository [(click here to fork now)](https://github.com/JordanCodeLab/portfolio-maker-api/fork)
2. Clone your forked code `git clone https://github.com/JordanCodeLab/portfolio-maker-api`
3. Create a new branch
4. Push your commits
5. Submit a new Pull Request

### Project Structure
```plaintext
portfolio-maker-api/
├─ src/                  
│   ├─ controllers/       # Controllers for handling requests
│   ├─ middlewares/       # Middlewares for request processing
│   ├─ models/            # Models that define the structure of data
│   ├─ repositories/      # Repositories for database operation abstraction
│   ├─ services/          # Services that contain business logic
│   ├─ utils/             # Utility functions
│   ├─ app.ts             # Initializes the libraries
│   ├─ router.ts          # Declaration of application endpoints
│   └─ server.ts          # Starts the application
├─ .env.dev               # Environment variable file for local configuration
├─ .env.prod              # Environment variable file for production configuration
├─ .env.example           # Example .env file for environment configuration
├─ package.json           # File that defines the dependencies and scripts of the project
├─ package-lock.json      # Automatically generated file containing the exact version of dependencies
├─ tsconfig.json          # TypeScript configuration file
```

## Contributors

<a href="https://github.com/JordanCodeLab/portfolio-maker-api/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=JordanCodeLab/portfolio-maker-api" />
</a>

## LICENSE
This project is licensed under the MIT License - see the LICENSE file for details.
