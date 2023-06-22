# Gramiphy - Git Documentation

Gramiphy is an Instagram clone developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack, with the addition of AI technology for automatic image tagging and categorization. This document provides an overview of the project's Git repository and its related workflows.

## Repository Structure

The Git repository for Gramiphy follows a standard structure to organize the source code and related files. Here is an outline of the repository structure:

```
├── backend/          # Node.js and Express.js server code
├── frontend/         # React.js client code
├── docs/             # Documentation and project-related files
└── .gitignore        # Git ignore file
```

The `backend/` directory contains the server-side code responsible for handling API requests, interacting with the database, and integrating with the AI models. This code is implemented using Node.js and Express.js.

The `frontend/` directory contains the client-side code developed with React.js. It includes components, styles, and pages that build the user interface of the Gramiphy web application.

The `docs/` directory is reserved for project-related documentation, including this Git document, API documentation, and any additional resources.

## Git Workflow

To maintain an organized and collaborative development process, we will follow a standard Git workflow. The primary branch for development is `main`. However, to facilitate feature development and bug fixing, we will utilize feature branches and pull requests. Here is an outline of the workflow:

1. Clone the repository to your local development environment:
   ```
   git clone <repository-url>
   ```

2. Create a new branch for each feature or bug fix:
   ```
   git checkout -b <branch-name>
   ```

3. Develop and make changes in the respective branch.

4. Regularly commit your changes with descriptive commit messages:
   ```
   git add .
   git commit -m "Brief description of changes"
   ```

5. Push the branch to the remote repository:
   ```
   git push origin <branch-name>
   ```

6. Once the feature or bug fix is complete, create a pull request (PR) on GitHub:
   - Go to the repository page on GitHub.
   - Click on the "New pull request" button.
   - Select the appropriate branches for the base and compare.
   - Provide a descriptive title and summary of the changes.
   - Review and address any feedback received during the PR review process.

7. Once the PR is approved, merge it into the `main` branch.

8. Regularly fetch and pull the latest changes from the `main` branch to keep your local repository up to date:
   ```
   git fetch origin
   git pull origin main
   ```

## Development Setup

To set up the development environment for Gramiphy, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Install the required dependencies for the backend and frontend:
   ```
   cd backend/
   npm install

   cd ../frontend/
   npm install
   ```

3. Configure the environment variables:
   - Create a `.env` file in the `backend/` directory and set the required variables, such as database connection details, API keys, and other configurations.

4. Start the backend server:
   ```
   cd backend/
   npm start
   ```

5. Start the frontend development server:
   ```
   cd frontend/
   npm start
   ```

6. Access the Gramiphy application by opening your web browser and navigating to `http://localhost:3000`.

## Conclusion

This Git documentation provides an overview of the Gramiphy project, its repository structure, and the recommended Git workflow for development.

 Following these guidelines will help maintain a collaborative and efficient development process for the team.