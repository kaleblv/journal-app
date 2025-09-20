# Copilot Instructions for Journal App

## Overview
This project is a simple React application bootstrapped with Parcel. It is designed to be lightweight and straightforward, making it ideal for quick prototyping or small-scale projects.

### Key Features
- **React 19**: The app uses React 19 for building UI components.
- **Parcel**: Parcel is used as the bundler, simplifying the build and development process.
- **TypeScript**: The project is configured with TypeScript for type safety.

## Project Structure
- `src/`: Contains all source files.
  - `App.tsx`: Main application component.
  - `index.tsx`: Entry point for the React application.
  - `index.html`: HTML template for the app.
  - `App.css`: Global styles for the app.
- `package.json`: Defines dependencies and scripts.
- `tsconfig.json`: TypeScript configuration.

## Development Workflow

### Start the Development Server
Run the following command to start the development server:
```bash
npm start
```
This will launch the app in development mode using Parcel.

### Build for Production
To create a production build, run:
```bash
npm run build
```
The output will be optimized and ready for deployment.

## Conventions and Patterns

### Component Structure
- Components are written as functional components.
- Use TypeScript for type annotations.

### Styling
- Global styles are defined in `App.css`.
- Inline styles or CSS modules are not used in this project.

### Strict Mode
The app is wrapped in React's `StrictMode` to highlight potential issues in the application.

## External Dependencies
- **React**: For building UI components.
- **Parcel**: For bundling and serving the application.

## Key Files
- `src/App.tsx`: Example of a functional component.
- `src/index.tsx`: Demonstrates how to render the React app into the DOM.

## Notes for AI Agents
- Focus on maintaining simplicity and readability in the code.
- Follow the existing patterns for adding new components or features.
- Ensure TypeScript types are used consistently.

Feel free to update this document as the project evolves.