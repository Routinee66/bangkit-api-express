<!---->

<div align="center">
    <h1>BASKARYA EXPRESS BACKEND API</h1>
    <h3>◦ HTTPStatus Exception: 404</h3>
    <h3>◦ Developed with the software and tools below.</h3>
</div>

<p align="center">
  <a href="https://skillicons.dev">
    <img src=https://skillicons.dev/icons?i=express,js,git,github />
  </a>
</p>

---

## Table of Contents

- [ Table of Contents](#-table-of-contents)
- [ Overview](#-overview)
- [ Features](#-features)
- [ repository Structure](#-repository-structure)
- [ Modules](#modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Running express-backend](#-running-express-backend)
  - [ Tests](#-tests)
- [ Roadmap](#-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

## Overview

HTTPStatus Exception: 404

---

## Features

HTTPStatus Exception: 404

---

## Repository Structure

```sh
└── express-backend/
    ├── app.js
    ├── config/
    │   └── firebaseConfig.js
    ├── controllers/
    │   ├── articleController.js
    │   ├── batikController.js
    │   ├── bookmarkController.js
    │   ├── searchController.js
    │   └── customController.js
    ├── exceptions/
    │   ├── AuthorizationError.js
    │   ├── ClientError.js
    │   ├── InvariantError.js
    │   └── NotFoundError.js
    ├── middleware/
    │   └── loggingMiddleware.js
    ├── package-lock.json
    ├── package.json
    ├── router/
    │   ├── articlesRouter.js
    │   ├── batikRouter.js
    │   ├── bookmarkRouter.js
    │   ├── searchRouter.js
    │   └── customRouter.js
    ├── services/
    │   └── firestore/
    │       ├── ArticlesService.js
    │       ├── BatikService.js
    │       ├── BookmarksService.js
    └────── └── CustomService.js

```

---

## Modules

<details closed><summary>Root</summary>

| File                                                                                         | Summary                   |
| -------------------------------------------------------------------------------------------- | ------------------------- |
| [package-lock.json](https://github.com/Baskarya/express-backend/blob/main/package-lock.json) | HTTPStatus Exception: 404 |
| [app.js](https://github.com/Baskarya/express-backend/blob/main/app.js)                       | HTTPStatus Exception: 404 |
| [tesdb.js](https://github.com/Baskarya/express-backend/blob/main/tesdb.js)                   | HTTPStatus Exception: 404 |
| [package.json](https://github.com/Baskarya/express-backend/blob/main/package.json)           | HTTPStatus Exception: 404 |

</details>

<details closed><summary>Router</summary>

| File                                                                                                | Summary                   |
| --------------------------------------------------------------------------------------------------- | ------------------------- |
| [batikRouter.js](https://github.com/Baskarya/express-backend/blob/main/router/batikRouter.js)       | HTTPStatus Exception: 404 |
| [searchRouter.js](https://github.com/Baskarya/express-backend/blob/main/router/searchRouter.js)     | HTTPStatus Exception: 404 |
| [bookmarkRouter.js](https://github.com/Baskarya/express-backend/blob/main/router/bookmarkRouter.js) | HTTPStatus Exception: 404 |
| [articlesRouter.js](https://github.com/Baskarya/express-backend/blob/main/router/articlesRouter.js) | HTTPStatus Exception: 404 |

</details>

<details closed><summary>Middleware</summary>

| File                                                                                                          | Summary                   |
| ------------------------------------------------------------------------------------------------------------- | ------------------------- |
| [loggingMiddleware.js](https://github.com/Baskarya/express-backend/blob/main/middleware/loggingMiddleware.js) | HTTPStatus Exception: 404 |

</details>

<details closed><summary>Controllers</summary>

| File                                                                                                             | Summary                   |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------- |
| [batikController.js](https://github.com/Baskarya/express-backend/blob/main/controllers/batikController.js)       | HTTPStatus Exception: 404 |
| [bookmarkController.js](https://github.com/Baskarya/express-backend/blob/main/controllers/bookmarkController.js) | HTTPStatus Exception: 404 |
| [articleController.js](https://github.com/Baskarya/express-backend/blob/main/controllers/articleController.js)   | HTTPStatus Exception: 404 |
| [searchController.js](https://github.com/Baskarya/express-backend/blob/main/controllers/searchController.js)     | HTTPStatus Exception: 404 |

</details>

<details closed><summary>Firestore</summary>

| File                                                                                                                | Summary                   |
| ------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| [ArticlesService.js](https://github.com/Baskarya/express-backend/blob/main/services/firestore/ArticlesService.js)   | HTTPStatus Exception: 404 |
| [BookmarksService.js](https://github.com/Baskarya/express-backend/blob/main/services/firestore/BookmarksService.js) | HTTPStatus Exception: 404 |
| [BatikService.js](https://github.com/Baskarya/express-backend/blob/main/services/firestore/BatikService.js)         | HTTPStatus Exception: 404 |

</details>

<details closed><summary>Config</summary>

| File                                                                                                | Summary                   |
| --------------------------------------------------------------------------------------------------- | ------------------------- |
| [firebaseConfig.js](https://github.com/Baskarya/express-backend/blob/main/config/firebaseConfig.js) | HTTPStatus Exception: 404 |

</details>

<details closed><summary>Exceptions</summary>

| File                                                                                                            | Summary                   |
| --------------------------------------------------------------------------------------------------------------- | ------------------------- |
| [ClientError.js](https://github.com/Baskarya/express-backend/blob/main/exceptions/ClientError.js)               | HTTPStatus Exception: 404 |
| [AuthorizationError.js](https://github.com/Baskarya/express-backend/blob/main/exceptions/AuthorizationError.js) | HTTPStatus Exception: 404 |
| [InvariantError.js](https://github.com/Baskarya/express-backend/blob/main/exceptions/InvariantError.js)         | HTTPStatus Exception: 404 |
| [NotFoundError.js](https://github.com/Baskarya/express-backend/blob/main/exceptions/NotFoundError.js)           | HTTPStatus Exception: 404 |

</details>

---

## Getting Started

**_Dependencies_**

Please ensure you have the following dependencies installed on your system:

## Dependencies

Below are the dependencies used in this Express API project, each serving a specific purpose:

- **express** (`^4.18.2`): Fast, unopinionated, minimalist web framework for Node.js.
- **body-parser** (`^1.20.2`): Node.js body parsing middleware, used to parse incoming request bodies.

- **axios** (`^1.6.2`): Promise-based HTTP client for the browser and Node.js, facilitating the making of HTTP requests.

- **firebase-admin** (`^11.11.1`): Firebase Admin SDK for Node.js, providing the necessary tools for managing Firebase services.

- **@google-cloud/storage** (`^7.7.0`): Google Cloud Storage client library for Node.js, enabling interaction with Google Cloud Storage.

- **multer** (`^1.4.5-lts.1`): Middleware for handling `multipart/form-data`, used for file uploads.

- **bcrypt** (`^5.1.1`): Library for hashing passwords, enhancing the security of user authentication.

- **sharp** (`^0.33.1`): High-performance image processing library, useful for resizing and manipulating images.

- **nanoid** (`^3.3.7`): A tiny, secure, URL-friendly unique string ID generator.

- **node-fetch** (`^3.3.2`): Lightweight module for making HTTP requests, compatible with the Fetch API.

### Development Dependencies

- **nodemon** (`^3.0.2`): Utility that monitors for changes in your source code and automatically restarts your server.

Please refer to [package.json](https://github.com/Baskarya/express-backend/blob/main/package.json) for more details on versioning and additional information about the project's dependencies.

### Installation

1. Clone the express-backend repository:

```sh
git clone https://github.com/Baskarya/express-backend
```

2. Change to the project directory:

```sh
cd express-backend
```

3. Install the dependencies:

```sh
npm install
```

### Running express-backend

```sh
node app.js
```

### Tests

```sh
npm test
```

---

## Project Roadmap

> - [x] `ℹ️  Task 1: Article API`
> - [x] `ℹ️  Task 2: Batik API`
> - [x] `ℹ️  Task 3: Bookmark API`
> - [x] `ℹ️  Task 4: Search API`
> - [x] `ℹ️  Task 5: Customization API`

---

## Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/Baskarya/express-backend/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Baskarya/express-backend/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/Baskarya/express-backend/issues)**: Submit bugs found or log feature requests for ROUTINEE66.

#### _Contributing Guidelines_

<details closed>
<summary>Click to expand</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone <your-forked-repo-url>
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear and concise message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

## License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#Top)

---
