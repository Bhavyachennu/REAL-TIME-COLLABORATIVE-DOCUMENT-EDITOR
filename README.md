# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR
NAME:Bhavya Harshitha Chennu , COMPANY:COTECH IT SOLUTIONS ,DURATION: Jan 05,2025 TO Feb 5,2025 ,DOMAIN:FRONTEND WEB DEVELOPMENT,Intern ID :CT08ISI
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/de1c7c0d-88a7-498d-b0a2-02aa9aec1d96" />
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/0ab16b70-ec47-44b5-9d42-acca21c673e8" />

## Real Time Collaborator

**Real Time Collaborator** is a powerful, real-time collaborative code editor that allows developers to collaborate, write, and debug code together in real time. Whether you're working with a team or collaborating on a project with friends, this app offers seamless collaboration and communication. It's built with modern technologies to provide a fast and smooth experience for developers.

### Features:
- Multiple users can join a room and edit code together.
- Real-time synchronization of code changes across all users.
- Syntax highlighting for different programming languages.
- Customizable themes for a personalized coding experience.
- A simple and intuitive user interface for effortless collaboration.
- Support for creating and joining rooms with a unique ID.
- Copy button to copy the room ID to your clipboard.
- Leave and rejoin rooms to continue collaboration.
- Real-time updates for users joining or leaving the room.

### Tech Stack:
- **Frontend**: React.js, Socket.io, React Router
- **Backend**: Node.js, Express.js
- **Code Editor**: CodeMirror (for syntax highlighting)
- **Real-Time Communication**: Socket.io for real-time collaboration
- **State Management**: React hooks (useState, useEffect)
- **Styling**: CSS, Styled Components (optional)

### Prerequisites:

- **Node.js** (v20.x.x) - [Download Node.js](https://nodejs.org/)
- **npm** (v10.x.x) - [Install npm](https://www.npmjs.com/)
- **pm2** (for managing the Node.js server) - Install using `npm i -g pm2`

### Installation:

#### Running Locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/Bhavyachennu/Real-Time-Collaborator.git
   ```

2. Navigate into the project directory:
   ```bash
   cd Real-Time-Collaborator
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add any necessary credentials or environment variables (example file: `.env.example`).

5. Start the React frontend:
   ```bash
   npm start
   ```

6. In another terminal, start the server:
   ```bash
   npm run server:dev
   ```

7. Open your browser and go to `http://localhost:3000` to access the app.

#### Running with Docker:

1. Install [Docker](https://www.docker.com/) on your machine.
2. Clone the repository and navigate to the project directory.
3. Build and run the Docker container:
   ```bash
   docker-compose up -d
   ```
4. Access the app at `http://localhost:3000`.

