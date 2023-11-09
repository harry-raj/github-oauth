# GitHub OAuth 2 Integration - Backend

Welcome to the backend portion of the GitHub OAuth 2 Integration project. This README will guide you through the setup and usage of the backend server, highlighting its features and technical aspects.

## Initial Setup

1. **Prerequisites**: Ensure you have Node.js and npm installed on your system. You can download them from [nodejs.org](https://nodejs.org/).

2. **Clone the Repository**: Clone the project repository from GitHub:

   ```bash
   git clone https://github.com/harry-raj/github-oauth.git
   ```

3. **Install Dependencies**: Navigate to the project directory and install the required dependencies using npm:

   ```bash
   cd backend
   npm install
   ```

4. **Run the Server**: Start the backend server by running:

   ```bash
   npm run start:dev
   ```

   The server will be available at `http://localhost:3000`.

## Project Structure

- **Controllers**: The backend server uses controllers to manage route handling and business logic.

- **Routes**: Routes are defined to handle API endpoints and interact with the frontend.

- **Models**: Data models are established using Mongoose, providing structure and validation for data stored in MongoDB.

## OAuth 2 Authentication

- OAuth 2 authentication is implemented on the server side to ensure data security and privacy during GitHub integration.

- Error handling is in place to provide informative error messages in case of unexpected issues.
