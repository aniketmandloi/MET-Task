# MET - Software Development Task

## Overview

Hello, i tried my best to complete the most of the requirements of the Test but there are some of the things I really could'nt complete in 4 hours but here's the code which I have written. Its a mern stack app with both front and the backend with user authentication using jwt.

## Prerequisites

Before you begin, make sure you have the following software installed on your machine:

- Node.js and npm (Node Package Manager): [Download and Install Node.js](https://nodejs.org/)
- MongoDB: [Download and Install MongoDB](https://www.mongodb.com/try/download/community)

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/aniketmandloi/MET-Task
    ```

2. Navigate to the project directory:

    ```bash
    cd MET - Software Development Test
    ```

3. Install backend dependencies:

    ```bash
    cd server
    npm install
    ```

4. Set up MongoDB:

    - Make sure your MongoDB server is running.
    - Go into your MongoDB cloud clusters.
    - Click on the `Database Access`, which is on the left of the sidebar. Click on `ADD NEW DATABASE USER` which will pop up a modal
    - Fill out the `Password Authentication` with your desired username and password for the database of this particular project.
    - Before saving this, click the `Built-in Role` dropdown, and select `Read and write to any database`.
    - Click on `Database`, and on the left side of the sidebar, click the `connect` button, which is beside View Monitoring. A modal popup will be displayed, then click `connect your application` and copy the code snippet you find there.

5. Configure the backend:

    - Create a `.env` file in the `server` directory.
    - Add the following variables to the `.env` file:

        ```env
        PORT=4000
        MONGODB_URL=<url you will copy from the cluster popup>
        ```

        Adjust the `PORT` and `MONGODB_URL` values as needed.

6. Start the backend server:

    ```bash
    npm start
    ```

    This will start the Node.js server at the specified port.

7. Install frontend dependencies:

    ```bash
    cd ../client
    npm install
    ```

8. Start the frontend:

    ```bash
    npm start
    ```

    This will start the React development server.

9. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to see the MERN stack app in action.

## Folder Structure

- **server:** Contains the Node.js server using Express.
- **client:** Contains the React application.
