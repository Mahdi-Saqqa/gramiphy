# Gramiphy (Work in Progress)

Gramiphy is an Instagram clone developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack, with the addition of AI technology for automatic image tagging and categorization. This web application aims to provide users with a platform to upload, share, and explore images while leveraging AI algorithms to enhance the user experience.

## Repository Structure

The Git repository for Gramiphy follows a structured organization of the source code and related files. Here is an overview of the repository structure:

```
├── client/           # React.js client code
├── server/           # Node.js and Express.js server code
├── python/           # Python AI application code
├── docs/             # Documentation and project-related files
└── .gitignore        # Git ignore file
```

The `client/` directory contains the client-side code developed with React.js. It includes components, styles, and pages that build the user interface of the Gramiphy web application.

The `server/` directory contains the server-side code responsible for handling API requests, interacting with the database, and serving the client-side code. This code is implemented using Node.js and Express.js.

The `python/` directory contains the Python AI application code. It includes the AI algorithms responsible for image analysis, tagging, and categorization. These algorithms utilize prebuilt AI APIs and custom models to generate descriptive tags based on the content of uploaded images.

The `docs/` directory is reserved for project-related documentation, including the README file, API documentation, and any additional resources.

## Functionality

Gramiphy aims to provide the following functionality:

1. User Registration and Authentication: Users can create accounts, log in, and log out of the application to access its features securely.

2. Image Upload and Sharing: Users can upload images to share them with others. The uploaded images will be processed by AI algorithms to generate descriptive tags automatically.

3. AI-powered Image Tagging: The Python AI application analyzes the uploaded images and generates relevant descriptive tags based on their content. This enables efficient search and organization of images on the platform.

4. Image Exploration: Users can explore images uploaded by others based on tags, categories, and popularity. The AI algorithms learn from user interactions, such as likes and comments, to suggest relevant images to each user.

5. Social Interactions: Users can like and comment on images, follow other users, and receive notifications about activity on their uploaded images.

6. User Profiles: Each user has a profile page where they can customize their profile picture, bio, and view their uploaded images and activity.

## Development Setup

To set up the development environment for Gramiphy, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Install the required dependencies for the client and server:
   ```
   cd client/
   npm install

   cd ../server/
   npm install
   ```

3. Configure the environment variables:
   - Create a `.env` file in the `server/` directory and set the required variables, such as database connection details, API keys, and other configurations.

4. Start the server:
   ```
   cd server/
   npm start
   ```

5. Start the client development server:
   ```
   cd client/
   npm start
   ```

6. Access the Gramiphy application by opening your web browser and navigating to `http://localhost:3000`.

## Python AI Application

The Python AI application in the `python/` directory is responsible for the image analysis, tagging, and categorization features in Gramiphy. It utilizes prebuilt AI APIs and custom AI models to generate descriptive tags based on the content of uploaded images.



To work with the Python AI application, follow these steps:

1. Install the required Python dependencies specified in the `python/requirements.txt` file:
   ```
   cd python/
   pip install -r requirements.txt
   ```

2. Implement and enhance the AI algorithms in the Python scripts within the `python/` directory.

3. Integrate the Python AI application with the server-side code in the `server/` directory to enable communication between the front-end and back-end.

## Conclusion

Gramiphy is an ongoing project that combines the MERN stack with AI technology to create an Instagram-like web application. The repository structure and development setup provided here allow for collaboration and further development of the client-side, server-side, and Python AI application components. With its AI-powered image tagging and categorization capabilities, Gramiphy aims to offer users a user-friendly platform for sharing, exploring, and discovering images.