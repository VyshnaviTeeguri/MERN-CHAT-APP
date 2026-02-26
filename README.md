Real-Time MERN Chat Application

Overview

This is a Real-Time Chat Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with WebSockets (Socket.io) for real-time communication. The app allows users to interact in private chats or group chat rooms, send messages and media files, and store chat history in the database for persistence.

This project is built as part of a SalesWinnr Technology Solutions Pvt. Ltd. assignment, with a focus on real-time chat applications like WhatsApp, Slack, and Teams.

Features
Must-Have Features:

Responsive Web Pages: Works across desktop, tablet, and mobile screens.

Authentication: Users can Sign Up and Sign In securely.

Real-Time Chat: Messages are delivered instantly using WebSockets.

Persistent Messages: Chat history is saved in MongoDB.

Additional Features:

Multiple Chat Rooms / Private Chats – Users can create private or group conversations.

Media Sharing – Send images and files in chats.

Typing Indicators – Shows when someone is typing.

User Profiles – Users can set display names and profile pictures.

Tech Stack

Frontend: React.js, Chakra UI / CSS (responsive design)

Backend: Node.js, Express.js

Database: MongoDB (Atlas / Local)

Real-Time Communication: Socket.io

Authentication: JWT (JSON Web Token)

File Uploads: Multer / Cloudinary (if using cloud storage)

Screenshots

(Add screenshots of the pages here: Login, Signup, Chat, Chat Room, Media Upload, etc.)

Setup Instructions (Local Development)
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

How to Use:

Sign up with a new account or login with existing credentials.

Create a chat room or start a private conversation.

Send text messages, images, or files.

Chat history is saved and can be accessed on login.

Folder Structure
client/        # React frontend
server/        # Node.js + Express backend
.env           # Environment variables for server
README.md