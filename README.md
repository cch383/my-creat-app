# My Create App (React)

This is a React application built with Vite.

## Project Setup

### Prerequisites

- Node.js (version 18 or higher recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd my-creat-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Development

To start the development server:

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the application.

## Building for Production

To build the application for production:

```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

## Deployment

This project is configured to automatically deploy to GitHub Pages using GitHub Actions.

1. Go to your repository **Settings**.
2. Navigate to **Pages** (under Code and automation).
3. Under **Build and deployment**, select **GitHub Actions** as the source.
4. Push your changes to the `main` branch.

The workflow defined in `.github/workflows/deploy.yml` will automatically build and deploy the application.
