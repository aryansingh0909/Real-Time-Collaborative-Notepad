# Collabify - Real Time Collaborative Notepad

This project is a real-time collaborative code editor designed to enhance team productivity and streamline coding workflows. Built using React.js and Node.js, it enables multiple users to collaborate seamlessly on code files in real-time.

## Features

- **Real-Time Code Collaboration:** Enables seamless live editing of code files among multiple users.  
- **Unique Room Generation:** Allows users to create or join collaborative sessions with distinct room IDs.  
- **User Presence Tracking:** Tracks active users in real time, displaying online/offline status.  
- **Join/Leave Notifications:** Provides instant alerts when users join or leave a session for better awareness.  
- **File Creation and Organization:** Supports creating, editing, and managing files within the collaborative environment.  
- **ZIP File Export:** Allows users to download the entire codebase as a ZIP file for easy sharing and backup.  
- **Integrated Code Execution:** Executes code directly within the editor using the Piston API, supporting multiple languages.  
- **Real-Time Status Updates:** Synchronizes all actions and updates across participants instantly using Socket.io.  
- **Intuitive User Interface:** Designed for a smooth and efficient collaboration experience.  
- **Technology Stack:** Built with React.js for the frontend, Node.js for the backend, and Socket.io for real-time communication.

## Installation

1. **Fork and clone this repostiory** 
3. **Set .env file:**
   Inside the client and server directories rename the `.env.example` file to `.env` and set the following environment variables:

    Frontend:

    ```bash
    VITE_BACKEND_URL=<your_server_url>
    ```

    Backend:

    ```bash
    PORT=3000
    ```

4. **Install dependencies:**
   Navigate to the frontend and backend directories separately and run:
    ```bash
     npm install
    ```
5. **Start the frontend and backend servers:**  
   Frontend:
    ```bash
    cd frontend
    npm run dev
    ```
    Backend:
    ```bash
    cd backend
    npm run dev
    ```
6. **Access the application:**
   Open a browser and enter the following URL:
    ```bash
    http://localhost:5173/
    ```
## Screenshots of UI 

Home Page
![image](https://github.com/user-attachments/assets/4b14cb15-4a32-412d-81ff-2a6c58077833)


