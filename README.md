# Food Unity Project

## Overview
Food Unity is a full-stack application designed to connect food enthusiasts with restaurants, recipes, and food-related services. This project consists of two main components: the **Client** and the **Server**.

---

## Table of Contents
1. [Client](#client)
    - [Features](#features)
    - [Setup Instructions](#setup-instructions)
2. [Server](#server)
    - [Features](#features-1)
    - [Setup Instructions](#setup-instructions-1)
3. [Technologies Used](#technologies-used)
4. [Contributing](#contributing)
5. [License](#license)

---

## Client

### Features
- User-friendly interface for browsing restaurants and recipes.
- Responsive design for mobile and desktop.
- Integration with the server for real-time data updates.
- Authentication and user profile management.

### Setup Instructions
1. Navigate to the `client` directory:
    ```bash
    git clone https://github.com/Azhar730/food-unity.git
    cd client
    Set up environment variables:
    - Create a `.env.local.example` to `.env.local` file in the `client` directory.
    - Add the following variables:
      ```
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm run dev
    ```
4. Open your browser and navigate to `http://localhost:3000`.

---

## Server

### Features
- RESTful API for managing food-related data.
- Secure authentication and authorization.
- Database integration for persistent storage.
- Scalable architecture for handling multiple requests.

### Setup Instructions
1. Navigate to the `server` directory:
    ```bash
    git clone https://github.com/Azhar730/food-unity.git
    cd server
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Set up environment variables:
    - Create a `.env` file in the `server` directory.
    - Add the following variables:
      ```
      PORT=5000
      DATABASE_URL=<your-database-url>
      JWT_SECRET=<your-secret-key>
      ```
4. Start the server:
    ```bash
    npm run dev
    ```
5. The server will run on `http://localhost:5000`.

---

## Technologies Used
- **Frontend**: React, Firebase, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add your message here"
    ```
4. Push to your branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).
