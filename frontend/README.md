# Cloudmart-fullstack

This repository contains the frontend application for Cloudmart, an e-commerce platform. It's built using React and Vite, with a focus on a modern and responsive user interface.

## Technologies Used

*   **Frontend Framework:** React
*   **Build Tool:** Vite
*   **Routing:** React Router DOM
*   **HTTP Client:** Axios
*   **UI Icons:** Lucide React
*   **Styling:** Tailwind CSS, PostCSS, Autoprefixer
*   **Linting:** ESLint

## Project Structure

The project follows a standard React application structure:

*   `public/`: Static assets.
*   `src/`: Main application source code.
    *   `assets/`: Images and other static assets.
    *   `components/`: Reusable React components, organized by page or functionality.
    *   `config/`: Application configuration (e.g., Axios).
    *   `utils/`: Utility functions (e.g., cart management, user authentication).
    *   `App.jsx`: Main application component.
    *   `main.jsx`: Entry point of the React application.
    *   `index.css`: Global styles.

## Installation

To get the project up and running locally, follow these steps:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Varunkk24/Cloudmart-fullstack.git
    cd Cloudmart-fullstack
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

## Usage

### Development Server

To start the development server with hot-reloading:

```bash
npm run dev
```

The application will be accessible at `http://localhost:5173/`.

### Build for Production

To build the application for production:

```bash
npm run build
```

This will generate optimized static files in the `dist` directory.

### Linting

To run ESLint for code quality checks:

```bash
npm run lint
```

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```
