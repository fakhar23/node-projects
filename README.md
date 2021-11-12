# Node Projects Collection

This repository consists of 4 Node.js projects focusing on different functionalities, ranging from a command line based note app to a fully functional task manager API.

## Projects

1. **Notes App**
    - Description: A simple command line app that allows users to take notes.
    - Dependencies:
        - `chalk: ^2.4.1`
        - `validator: ^10.8.0`
        - `yargs: ^12.0.2`
    - Usage: 
        ```bash
        node notes-app.js --title="Your Title" --body="Your Note Body"
        ```

2. **Weather App**
    - Description: Fetches weather forecast for a given address using Mapbox and Darksky APIs.
    - Dependencies:
        - `request: ^2.88.0`
    - Usage:
        ```bash
        node weather-app.js "Your Address"
        ```

3. **Web Server (Weather App)**
    - Description: A web server implementation of the Weather App using Express.js.
    - Dependencies:
        - `express: ^4.16.4`
        - `hbs: ^4.0.1`
        - `request: ^2.88.0`
    - Dev Dependencies:
        - `nodemon: ^1.2.0`
    - Available routes:
        - `/` - Home
        - `/about` - About
        - `/help` - Help
        - `/weather` - Weather Information
        - `/products` - Product Search
    - Usage:
        ```bash
        npm start
        ```

4. **Task Manager API**
    - Description: A comprehensive API for task management with functionalities including user authentication, profile management, and CRUD operations on tasks.
    - Dependencies:
        - `@sendgrid/mail: ^6.3.1`
        - `bcryptjs: ^2.4.3`
        - `express: ^4.16.4`
        - `jsonwebtoken: ^8.4.0`
        - `mongodb: ^3.1.10`
        - `mongoose: ^5.3.16`
        - `multer: ^1.4.1`
        - `sharp: ^0.21.1`
        - `validator: ^10.9.0`
    - Dev Dependencies:
        - `env-cmd: ^8.0.2`
        - `nodemon: ^1.18.9`
    - Features:
        - User Registration & Authentication
        - Password hashing
        - JWT based session management
        - User profile & task management
    - Usage:
        ```bash
        npm run dev
        ```

## Setup

1. Clone the repository:
    ```bash
    git clone [repository_url]
    ```

2. Navigate into the respective project directory and install the necessary packages:
    ```bash
    cd [project_directory]
    npm install
    ```

3. Run the project (as per individual project's usage instructions).

Enjoy exploring the projects! Feel free to reach out with any questions or feedback.
