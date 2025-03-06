# IOD Capstone/ShePlays: Football - Frontend

This is the frontend repository for the **ShePlays: Football** capstone project. The app provides a platform for women’s tackle football players to discover teams, follow players, track schedules, and access workout and mental health resources.

## Features

- **Player Card Swipe**: Users can swipe through player cards to follow players, and a list of followed players will be displayed as they swipe right.
- **Dashboard**: Displays user welcome messages and links to all the features of the app. Also includes testimonials.
- **Where We Play**: A world map showing locations of football teams, helping users find teams near them.
- **Master Your Game**: Includes workout and technical drill videos along with mental health articles for players.
- **Game Day**: Displays schedules for upcoming games.

## Tech Stack

- **React**: The app is built using React for efficient and dynamic UI updates.
- **Vite**: A fast build tool that provides hot module replacement (HMR) during development.
- **Axios**: Used for making HTTP requests to interact with the backend API.
- **React Router**: Enables client-side routing to handle navigation between pages.
- **CSS/SCSS**: For styling the application.

## Installation

Follow these steps to set up the project locally:

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Cloning the Repository

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/vroces/IOD-Capstone-FE.git

Installing Dependencies:
To install the necessary dependencies, run the following command:
  npm install

This will install the required dependencies listed in the package.json file:

axios: ^1.8.1
react: ^19.0.0
react-dom: ^19.0.0
react-router-dom: ^7.2.0
vite: ^6.2.0

Running the application:
Start the develompent server: 
  npm run dev
      The app should now be running at http://localhost:5173. Open this URL in your browser to see the frontend in action. 

Development Server
The app uses Vite for fast development, and with Vite’s Hot Module Replacement (HMR), any changes made to the code will be immediately reflected in the browser.


frontend/
  ├── public/                # Static assets (images)
  ├── src/                   # Source files for the app
  │   ├── assets/            # Static files like images or icons
  |   |--context/            # AuthContext
  │   ├── components/        # Reusable UI components (buttons, forms, etc.)
  │   ├── pages/             # Pages of the app (Dashboard, Player Cards, etc.)
  |   |--routes/             # Routes
  │   ├── App.jsx             # Main app component, root of the app
  │   ├── main.jsx           # Entry point of the React app
  │   └── styles/            # Global and component-specific styles
  ├── .env                   # Environment variables file
  ├── package.json           # NPM scripts and dependencies for frontend
  └── vite.config.js         # Vite configuration file

Scripts
The following scripts are available for managing the development and build process:
npm run dev: Starts the Vite development server. Open the app at http://localhost:5173.
npm run build: Builds the app for production, optimizing the code for performance.
npm run preview: Previews the production build locally.
npm run lint: Runs ESLint on the codebase to check for linting errors.

React + Vite Setup
This project is set up with Vite for fast development and React for building the user interface. Vite provides fast builds and HMR, while React allows us to efficiently manage the UI.






