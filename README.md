# SARAHAH

SARAHAH - Anonymous Messaging Application 💬
Table of Contents
Introduction 📖
Features ✨
Architecture 🏛️
Installation ⚙️
Usage 🚀
Technologies 💻

Introduction 📖
SARAHAH is a web application that allows users to send and receive anonymous messages. Inspired by the original SARAHAH platform, this project implements a secure messaging system with modern web development technologies. The application follows the Model-View-Controller (MVC) architecture, providing clean code separation and scalable functionality.

Features ✨
Anonymous Messaging: Users can send and receive messages anonymously 🕵️‍♂️.
User Authentication: Secure user login and session management using cookies.
RESTful API: Backend API for handling message creation, retrieval, and user interactions 🔄.
QR Code Generation: Generate QR codes for users to share their messaging profile 📲.
Dynamic Views: Responsive user interface with dynamic templates 🖼️.
Architecture 🏛️
The application follows the MVC architecture:

Model: Handles data schema and communication with MongoDB using Mongoose 🗂️.
View: Dynamic user interface rendered with EJS templates 🎨.
Controller: Manages API routes, user authentication, and session management ⚡.
Authentication 🔑
Authentication is implemented using cookie-based sessions, with session data stored securely in MongoDB🛡️.

Database 💾
MongoDB: The application uses MongoDB for data storage, with Mongoose as an object data modeling (ODM) library for managing user and message data.
Installation ⚙️
Clone the repository:
git clone https://github.com/mennaseif/sarahah.git
cd sarahah
Install dependencies:
npm install
Configure environment variables: Create a .env file in the root directory and add the following variables:
DB_CONNECTION=<your_mongodb_connection_string>
SESSION_SECRET=<your_session_secret>
Run the application:
npm start
The application will be available at http://localhost:3001 🌐.

Usage 🚀
Register/Login: Users can create an account or log in to an existing one 📝.
Send/Receive Messages: Once logged in, users can send anonymous messages or view their received messages ✉️.
QR Code Sharing: Users can share a QR code for others to send messages 📲.

Technologies 💻
Backend: Node.js, Express
Frontend: EJS (Embedded JavaScript templates)
Database: MongoDB with Mongoose
Session Management: Cookie-based sessions 🍪
Additional Libraries: QR Code generation, CORS for cross-origin requests 🌍






