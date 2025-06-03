## <b>WhatsApp clone build using MERN stack</b>

#### 🧾 Description

Its build using MERN stack and uses <a href='https://socket.io/'>socket.io</a> for realtime messaging, online statuses, typing indicators, notifications etc.

#### ✨ Features

- [x] User authentication.
- [x] Search for users to chat with.
- [x] Chat in realtime with <a href='https://socket.io/'>socket.io</a>.
- [x] User's realtime online/offline status in private chat.
- [x] Responsive upto a limit.
- [x] And most importantly 😎 Feels just like whatsapp-web (or Desktop app).

#### ⚙ Tools and Technologies used

###### Frontend

1. [React.js](https://reactjs.org/)
2. [Material-ui](https://mui.com/)

###### Backend

1. [Node.js](https://nodejs.org/en/)
2. [Express.js](https://expressjs.com/)
3. [MongoDB](https://www.mongodb.com/)
4. [Socket.io](https://socket.io/)
5. [Docker](https://www.docker.com/)

#### 🛠 Installation and setup

You can run this application either using Docker or traditional npm setup.

##### Using Docker:

1. Make sure you have Docker and Docker Compose installed on your machine.
2. Clone the repo to your local machine.
3. Create a .env file inside the server folder with your MongoDB credentials:
   ```
   DB_USERNAME=<your-db-username>
   DB_PASSWORD=<your-db-password>
   ```
4. Run the application using Docker Compose:
   ```bash
   cd server
   docker compose up
   ```
   This will start all the required services (backend, frontend, and socket) in containers.

##### Traditional Setup:

1. Clone the repo to your local machine.
2. Install the required dependency for server using :

   ```javascript
   cd server
   npm install --legacy-peer-deps
   ```

3. Install the required dependency for client using :

   ```javascript
   cd client
   npm install --legacy-peer-deps
   ```

4. Install the required dependency for socket using :

   ```javascript
   cd socket
   npm install --legacy-peer-deps
   ```

5. Start the express server using :

   ```javascript
   npm start
   ```

6. Start the react development server using:

   ```javascript
   cd client
   npm start
   ```

7. Start the socket using:

   ```javascript
   cd socket
   npm start
   ```

