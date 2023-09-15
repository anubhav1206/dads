# supreme-octo-fishstick

## Project Description
This project consists of a frontend (built with React) and a backend (powered by Flask) designed to serve as a website for querying a database of arithmetic dynamical systems. Currently, the backend uses static data, but the goal is to eventually connect it to a PostgreSQL database.

## Dependencies
- **Backend Dependencies**:
  - Python dependencies: flask, flask_cors

- **Frontend Dependencies**:
  - Node.js
  - React
  - Material-UI (MUI)

## Running the Backend
To run the backend, follow these steps:

1. Open a terminal.

2. Navigate to the "backend" folder:

   ```
   cd backend
   ```

3. Run the Flask server:

   ```
   python server.py
   ```

   This will start the backend server.

## Running the Frontend
To run the frontend, follow these steps:

1. Open a terminal.

2. Navigate to the "frontend" folder:

   ```
   cd frontend
   ```

3. If it's your first time running the frontend, install Node.js dependencies:

   ```
   npm install
   ```

4. Start the frontend development server:

   ```
   npm run start
   ```

   This will open the website automatically in your default web browser.

## Docker Instructions
You can also run this project using Docker containers. Here's how:

### Running the Backend in Docker
1. Build the Docker image for the backend:

   ```
   docker build -t supreme-octo-fishstick-backend ./backend
   ```

2. Run the backend container:

   ```
   docker run -p 5000:5000 supreme-octo-fishstick-backend
   ```

   This will start the Flask backend in a Docker container.

### Running the Frontend in Docker
1. Build the Docker image for the frontend:

   ```
   docker build -t supreme-octo-fishstick-frontend ./frontend
   ```

2. Run the frontend container:

   ```
   docker run -p 3000:3000 supreme-octo-fishstick-frontend
   ```

   This will start the React frontend in a Docker container.

Make sure to adjust any environment variables or database configurations in your Docker setup as needed, especially when connecting to a PostgreSQL database.

