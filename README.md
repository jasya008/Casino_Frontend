# Casino Project (Frontend side)

This is a React-based web application for a casino platform, featuring game listings, user authentication, and internationalization.

## Features

*   User Authentication (Login, Registration, Password Reset)
*   Game Listings and Details
*   Casino Information Pages
*   Internationalization (i18n)
*   Responsive UI with Material UI components
*   Form validation with React Hook Form and Zod
*   Mock API server for development

## Technologies Used

### Frontend
*   **React**: A JavaScript library for building user interfaces.
*   **Vite**: A fast build tool for modern web projects.
*   **SCSS**: CSS preprocessor for styling.

### UI & Styling
*   **Material UI**: A comprehensive suite of UI tools to help you ship new features faster.
*   **Emotion**: A performant and flexible CSS-in-JS library used by Material UI.

### State Management & Forms
*   **React Hook Form**: Performant, flexible and extensible forms with easy-to-use validation.
*   **Zod**: A TypeScript-first schema declaration and validation library.

### Routing
*   **React Router DOM**: Declarative routing for React.

### Internationalization (i18n)
*   **i18next**: An internationalization framework for JavaScript.
*   **React i18next**: Integration layer for i18next and React.
*   **i18next-browser-languagedetector**: Language detector for i18next in the browser.
*   **i18next-http-backend**: Backend to load translations from a remote server.

### API Communication
*   **Axios**: Promise-based HTTP client for the browser and Node.js.

### Animations
*   **React Spring**: A spring physics based animation library.

### Other Utilities
*   **React Copy To Clipboard**: Copy text to clipboard easily.
*   **React Toastify**: Notification system.
*   **Swiper**: Modern touch slider.

### Development / Mock Backend
*   **JSON Server**: Full fake REST API with zero coding in less than 30 seconds.
*   **json-server-auth**: Adds authentication to JSON Server.
*   **Concurrently**: Run multiple commands concurrently.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Node.js (LTS recommended)
*   npm (comes with Node.js)

### Installation

1.  **Clone the repository:**
    \`\`\`bash
    git clone <repository-url>
    cd CASINO
    \`\`\`
2.  **Install dependencies:**
    \`\`\`bash
    npm install
    \`\`\`

### Running the Project

To run both the frontend development server and the mock API server concurrently:

```bash
npm run start
```

This command will:
*   Start the React development server (usually on `http://localhost:5173`).
*   Start the JSON Server mock API (usually on `http://localhost:4080`).

#### Running Separately (Optional)

You can also run the frontend and backend servers independently:

*   **Frontend Development Server:**
    ```bash
    npm run dev
    ```
*   **Mock API Server:**
    ```bash
    npm run server
    ```

## Project Structure Overview

*   \`public/\`: Static assets, including `locales` for internationalization and `static/images`.
*   \`src/\`: Main application source code.
    *   \`assets/\`: Image and SVG assets.
    *   \`components/\`: Reusable UI components, organized by feature or category (e.g., `Authorisation`, `casinoeForGames`).
    *   \`pages/\`: Top-level components representing different views/routes of the application.
    *   \`routes/\`: Application routing configuration.
    *   \`context/\`: React Context API for global state.
    *   \`i18n.js\`: i18next configuration.
*   \`data/\`: Contains `db.json` for the JSON Server mock API.

## Linting

To run ESLint for code quality checks:

```bash
npm run lint
```
