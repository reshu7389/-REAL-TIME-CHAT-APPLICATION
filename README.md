# -REAL-TIME-CHAT-APPLICATION
"COMPANY": CODTECH IT SOLUTIONS
"NAME": RESHU SINGH
"INTERN ID": CT04DH1157
"DOMAIN": MERN STACK WEB DEVELOPEMENT
"DURATION": 4 WEEKS
"MENTOR": NEELA SANTOSH

Project Title: Real-Time Chat Application
📝 Project Description:
The Real-Time Chat Application is a web-based communication tool developed using React for the frontend and Socket.IO with Node.js for the backend. This project enables live, two-way communication between users, simulating the core functionality of modern messaging platforms like WhatsApp Web, Slack, or Discord in a simplified form.

The core objective of this project is to implement live messaging capabilities between multiple users by leveraging WebSockets through the Socket.IO library. Unlike traditional HTTP communication, where messages must be constantly polled or refreshed, this application maintains a persistent, real-time connection between client and server, allowing messages to be sent and received instantly without delay.

🛠️ Tools and Technologies Used:
Frontend:

React.js (for UI rendering and state management)

Socket.IO-client (for establishing WebSocket connection)

HTML/CSS (for structure and styling)

Backend:

Node.js (for server runtime)

Express.js (for setting up a lightweight API server)

Socket.IO (for real-time bi-directional communication)

CORS (to handle cross-origin requests between client and server)

💡 Key Features:
Live Messaging: Users can send and receive messages instantly with no refresh or reload.

Multiple User Support: The system can handle multiple users connected simultaneously.

Simple UI: A clean and minimal user interface that allows users to type and send messages quickly.

Real-Time Broadcast: When one user sends a message, it is broadcast in real time to all other connected users.

Component-Based Design: The React structure uses reusable components like Chat, App, and input handlers, making the code easy to maintain and extend.

🔧 How It Works:
When a user visits the chat interface, a WebSocket connection is established with the server using Socket.IO.

The user types a message and hits "Send". This triggers a send_message event which is emitted to the server.

The server listens for this event and immediately broadcasts the message to all other connected clients using the receive_message event.


Other clients receive the message in real time, and it appears on their screens without any page refresh.

The application also manages user sessions using Socket.IO socket IDs and handles disconnections gracefully.

#OUTPUT
<img width="1909" height="866" alt="Image" src="https://github.com/user-attachments/assets/68070331-c1c7-4921-b486-8ab1a0fedcbe" />
