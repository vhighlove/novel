# Health Beauty Studio Landing

## Overview

This project is a landing page for a health beauty studio. It is built with a modern tech stack to ensure high performance, security, and maintainability.

## Tech Stack

### Backend
- **Golang**: Used for building the backend services.
- **Auth0**: Used for authentication and authorization.

### Frontend
- **Next.js**: A React framework for server-side rendering and static site generation.
- **TypeScript**: A statically typed superset of JavaScript.
- **Jotai**: A state management library for React.

## Getting Started

### Prerequisites
- Node.js
- npm or yarn
- Go

### Installation

1. **Clone the repository:**
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install frontend dependencies:**
    ```sh
    cd frontend
    npm install
    # or
    yarn install
    ```

3. **Install backend dependencies:**
    ```sh
    cd backend
    go mod tidy
    ```

### Running the Application

1. **Start the backend server:**
    ```sh
    cd backend
    go run main.go
    ```

2. **Start the frontend server:**
    ```sh
    cd frontend
    npm run dev
    # or
    yarn dev
    ```

### Environment Variables

Create a `.env` file in both the `frontend` and `backend` directories and add the necessary environment variables as specified in the `.env.example` files.

## Project Structure

### Backend
- `main.go`: Entry point for the backend server.
- `handlers/`: Contains the HTTP handlers.
- `models/`: Contains the data models.

### Frontend
- `pages/`: Contains the Next.js pages.
- `components/`: Contains the React components.
- `store/`: Contains the Jotai atoms and state management logic.

## Authentication

This project uses Auth0 for authentication. Make sure to configure your Auth0 credentials in the `.env` files.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.