# WanderLust
# Major Project

This is a full-stack web application built with Node.js, Express.js, and MongoDB using the MVC architecture. The project includes authentication and authorization functionalities along with complete CRUD operations.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- MVC architecture
- User authentication and authorization
- CRUD operations
- File uploads with Cloudinary
- Session management
- Flash messages for notifications

## Technologies Used

- **Node.js**: JavaScript runtime
- **Express.js**: Web framework for Node.js
- **MongoDB**: NoSQL database
- **Mongoose**: ODM for MongoDB
- **EJS**: Embedded JavaScript templating
- **Passport**: Authentication middleware
- **Multer**: Middleware for handling multipart/form-data
- **Cloudinary**: Cloud storage for images

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Rohit-Mangasule/wonderlust
    
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the root directory and add the following:

    ```env
    CLOUDINARY_CLOUD_NAME=your_cloud_name
    CLOUDINARY_API_KEY=your_api_key
    CLOUDINARY_API_SECRET=your_api_secret
    MONGO_URI=your_mongodb_uri
    SESSION_SECRET=your_session_secret
    ```

4. **Run the application:**

    ```bash
    node app.js
    ```

    The application should now be running on [http://localhost:3000](http://localhost:3000).

## Usage

- Visit [http://localhost:3000](http://localhost:3000) to view the application.
- Register a new user or log in with existing credentials.
- Perform CRUD operations as per the functionalities provided in the application.




