# Real-Time Chat Application (WebSockets)

## Description
This is a real-time private chat application where two users can communicate using a shared random username. Messages are transferred instantly using WebSockets without page reload.

## Tech Stack
- Node.js
- Express.js
- WebSockets (Socket.io)

## Features
- Real-time messaging
- Private chat using shared username
- Low-latency communication
- No page refresh required

## How It Works
- User enters a random username
- Shares it with another user
- Both users connect using the same username
- Messages are exchanged privately in real-time

## Installation
git clone https://github.com/Akhilesh9112/real-time-chat-app.git  
cd real-time-chat-app  
npm install  
npm start  

## Project Structure
/src  
  /controllers  
  /routes  
  /sockets  
server.js  

## Future Improvements
- Add authentication system  
- Add group chat feature  
- Add message storage (database)  
- Improve UI  
