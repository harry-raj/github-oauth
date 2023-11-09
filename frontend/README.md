# GitHub OAuth 2 Integration - Frontend

Welcome to the frontend portion of the GitHub OAuth 2 Integration project. This README will guide you through the setup and usage of the frontend application, showcasing its features and technical aspects.

## Initial Setup

1. **Prerequisites**: Ensure you have Node.js and npm installed on your system. You can download them from [nodejs.org](https://nodejs.org/).

2. **Clone the Repository**: Clone the project repository from GitHub:

   ```bash
   git clone https://github.com/harry-raj/github-oauth.git
   ```

3. **Install Dependencies**: Navigate to the project directory and install the required dependencies using npm:

   ```bash
   cd frontend
   npm install
   ```

4. **Run the Application**: Start the Angular development server by running:

   ```bash
   npm run start
   ```

   The application will be available at `http://localhost:4200`.

## Project Structure

- **Components**: The frontend application is organized into components, following Angular's component-based architecture. Each component handles specific aspects of the user interface and functionality.

- **Services**: Dedicated services are used to make API calls and manage data. These services ensure data is fetched and processed efficiently.

## User Authentication

- **OAuth 2 Authentication**: User authentication is handled via GitHub OAuth 2. When you click the "Connect" button, you'll be redirected to GitHub for authentication.

## Additional Features

- **User-Friendly UI**: Angular Material provides an elegant and responsive user interface.

