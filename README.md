**MERN Chat Application**

**Overview**

This is a Real-Time Chat Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with WebSockets (Socket.io) for real-time communication. The app allows users to interact in private chats or group chat rooms, send messages and media files, and store chat history in the database for persistence.

This project is built as part of a SalesWinnr Technology Solutions Pvt. Ltd. assignment, with a focus on real-time chat applications like WhatsApp, Slack, and Teams.

**Features**
Must-Have Features:

Responsive Web Pages: Works across desktop, tablet, and mobile screens.

Authentication: Users can Sign Up and Sign In securely.

Real-Time Chat: Messages are delivered instantly using WebSockets.

Persistent Messages: Chat history is saved in MongoDB.

**Additional Features:**

Multiple Chat Rooms / Private Chats – Users can create private or group conversations.

Media Sharing – Send images and files in chats.

Typing Indicators – Shows when someone is typing.

User Profiles – Users can set display names and profile pictures.

**Tech Stack**

Frontend: React.js, Chakra UI / CSS (responsive design)

Backend: Node.js, Express.js

Database: MongoDB (Atlas / Local)

Real-Time Communication: Socket.io

Authentication: JWT (JSON Web Token)

**Screenshots:**

<img width="1870" height="885" alt="image" src="https://github.com/user-attachments/assets/36805b2b-1167-4720-819d-d09d6ea4e3db" />

<img width="901" height="781" alt="image" src="https://github.com/user-attachments/assets/7bfc5e4c-6ff4-4aed-a354-3d572c9feab7" />

![img-3](https://github.com/user-attachments/assets/53e9217c-6cf7-4ac2-9ede-a5bced4e564a)
![img-2](https://github.com/user-attachments/assets/316f034a-43ae-41d6-bdd8-20a7b1caca83)
![img-1](https://github.com/user-attachments/assets/8c3d5658-2ead-436e-99df-c9cd507a7c82)
![img-6](https://github.com/user-attachments/assets/18f26329-7c61-4819-ac4a-78b738c8df24)
![img-5](https://github.com/user-attachments/assets/717cfc80-f464-49ab-8a8a-4a4eaeebce42)
![img-4](https://github.com/user-attachments/assets/4c5d63c9-0ffc-42e0-9b97-d5be4ad617f2)


**Setup Instructions (Local Development)**
Prerequisites:

Node.js v22.x

npm v9.x or higher

MongoDB (local or Atlas cluster)

Backend Setup:

Open terminal in the server folder.

Install dependencies:

npm install

Create a .env file with the following variables:

PORT=5000
MONGO_URI=<Your MongoDB Connection String>
JWT_SECRET=<Your JWT Secret>

Start the server:

npm run dev

Server will run on http://localhost:5000.

Frontend Setup:

Open terminal in the client folder.

Install dependencies:

npm install

Start the React app:

npm start

App will run on http://localhost:3000.

**How to Use:**

Sign up with a new account or login with existing credentials.

Create a chat room or start a private conversation.

Send text messages, images, or files.

Chat history is saved and can be accessed on login.

Folder Structure
client/        # React frontend
server/        # Node.js + Express backend
.env           # Environment variables for server
README.md
