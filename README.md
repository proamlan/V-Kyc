# One-to-One Video Call with Node.js and Socket.IO

## Overview

This project demonstrates a simple one-to-one video call application using Node.js, Socket.IO, and WebRTC. It establishes direct peer-to-peer connections for real-time audio and video communication, allowing two users to have a private video call within their web browsers.

## Key Technologies

Node.js: Server-side JavaScript runtime environment.
Socket.IO: Real-time bidirectional communication library for web applications.
WebRTC: Web Real-Time Communication API for peer-to-peer audio/video communication.
PeerJS: Server-side PeerJS library (optional for signaling server setup).

## Project Structure

index.html: Client-side HTML file for user interface.
style.css: Optional CSS file for styling.
script.js: Client-side JavaScript file for handling video calls.
app.js: Node.js server file for handling socket connections and signaling.

## Setup Instructions

Install dependencies:

Bash
npm install express socket.io peerjs # If using PeerJS for signaling
Use code with caution. Learn more

Run the server:

npm i express ejs socket.io uuid peer

Bash
node server.js
Use code with caution. Learn more
Access the application:
Open http://localhost:3000 (or the specified port) in two separate browser windows or tabs.

## Usage

In each browser window, click the "Start Call" button.
Enter the unique peer ID of the other user in the respective input field.
Click the "Call" button to initiate the video call.
Enjoy your private video conversation!

## Additional Notes

TURN server: For environments where direct peer-to-peer connections are restricted, consider using a TURN server to relay media traffic.
Signaling server: Explore using a dedicated signaling server (like PeerJS) for more complex features and scalability.
Error handling and security: Implement robust error handling and security measures for production-level applications.

## Contribute

Feel free to contribute to this project by suggesting improvements, fixing bugs, or adding new features.

## Enjoy!
