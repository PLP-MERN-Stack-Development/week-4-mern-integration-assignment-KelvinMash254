# MERN Blog Application

This is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that serves as a blog platform. It allows users to create, read, update, and delete blog posts, as well as manage user authentication and comments.

## Features

- **Full CRUD Functionality**: Users can create, read, update, and delete blog posts.
- **User Authentication**: Secure user registration and login functionality.
- **Image Uploads**: Users can upload images to their blog posts.
- **Comments**: Users can leave comments on blog posts.
- **Responsive Design**: The application is designed to be responsive and user-friendly.

## Project Structure

The project is organized into two main directories: `client` for the React front-end and `server` for the Express back-end.

### Client

- `public/`: Contains static files such as images and the HTML file.
- `src/`: Contains the React source code.
  - `components/`: Reusable components.
  - `pages/`: Page components for different views.
  - `hooks/`: Custom React hooks.
  - `services/`: API service files for HTTP requests.
  - `context/`: React context providers for global state management.
  - `App.jsx`: Main application component.

### Server

- `config/`: Configuration files for the server.
- `controllers/`: Route controllers for handling requests.
- `models/`: Mongoose models for MongoDB schemas.
- `routes/`: API route definitions.
- `middleware/`: Custom middleware functions.
- `utils/`: Utility functions.
- `server.js`: Main server file to initialize the application.

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- MongoDB (local installation or Atlas account)
- npm or yarn
- Git

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd mern-blog
   ```

2. Install server dependencies:
   ```
   cd server
   npm install
   ```

3. Install client dependencies:
   ```
   cd client
   npm install
   ```

4. Set up the MongoDB database and update the configuration in `server/config`.

### Running the Application

1. Start the server:
   ```
   cd server
   npm start
   ```

2. Start the client:
   ```
   cd client
   npm start
   ```

The application should now be running on `http://localhost:3000`.

## Documentation

For detailed instructions and requirements, refer to the `Week4-Assignment.md` file.

## Screenshots

Include screenshots of the working application here.

## License

This project is licensed under the MIT License.