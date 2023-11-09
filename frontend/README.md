# GitHub OAuth 2 Integration - Frontend

Welcome to the frontend portion of the GitHub OAuth 2 Integration project. This README will guide you through the setup and usage of the frontend application, showcasing its features and technical aspects.

## Technical Expertise

The frontend portion of this project demonstrates expertise in the following technologies and best practices:

- **Angular v15.2**: Utilized the latest version of Angular to leverage new features, performance enhancements, and maintain codebase compatibility with the latest standards.

- **Angular Material**: Employed Angular Material to ensure a polished, responsive, and consistent user interface with modern design principles.

- **Modular Architecture**: Structured the application into feature modules, making it highly maintainable and scalable as it grows.

- **User Authentication**: Implemented secure user authentication using OAuth 2 with GitHub, following best practices for authentication and authorization.

- **Real-Time Updates**: Integrated WebSockets to provide real-time updates to users, enhancing the user experience with instant notifications and live data feeds.

- **User-Friendly UI**: Designed a user-friendly UI with Angular Material, providing an elegant and responsive interface.

- **Data Validation**: Ensured data integrity through robust input validation both on the frontend and backend, enhancing data consistency and user experience.


## Initial Setup

1. **Prerequisites**: Ensure you have Node.js and npm installed on your system. You can download them from [nodejs.org](https://nodejs.org/).

2. **Clone the Repository**: Clone the project repository from GitHub:

   ```bash
   git clone https://github.com/your/repo.git
   ```

3. **Install Dependencies**: Navigate to the project directory and install the required dependencies using npm:

   ```bash
   cd frontend
   npm install
   ```

4. **Run the Application**: Start the Angular development server by running:

   ```bash
   ng serve
   ```

   The application will be available at `http://localhost:4200`.

## Project Structure

- **Components**: The frontend application is organized into components, following Angular's component-based architecture. Each component handles specific aspects of the user interface and functionality.

- **Services**: Dedicated services are used to make API calls and manage data. These services ensure data is fetched and processed efficiently.

- **Modules**: Angular modules structure the application, providing modularity and enabling feature-based development.

## User Authentication

- **OAuth 2 Authentication**: User authentication is handled via GitHub OAuth 2. When you click the "Connect" button, you'll be redirected to GitHub for authentication.

- **Real-Time Updates**: The application features real-time updates through WebSocket integration, offering live data feeds and instant notifications.

## Additional Features

- **User-Friendly UI**: Angular Material provides an elegant and responsive user interface.

- **Data Validation**: Input validation is implemented to maintain data integrity and consistency.

## Testing and Verification

- Create a GitHub testing account for testing purposes.

- Import open source/public repositories to ensure the authentication and integration work correctly.

