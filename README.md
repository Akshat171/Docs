Google Docs Clone - React.js,Socket.js , Node.js, MongoDB
![image](https://github.com/Akshat171/Docs/assets/81281246/5a60eca4-bb11-427b-a4b9-ffcf6e37a152)
This is a real-time collaborative document editing web application, similar to Google Docs, built using React.js, Socket.io, Node.js, and MongoDB. Users can create and edit documents in real-time, and changes made by one user will be instantly reflected on the documents of other connected users.

Features
Real-time collaboration: Multiple users can edit the same document simultaneously in real-time.
Document sharing: Users can share the document URL with others to collaborate.
Rich text editing: Supports formatting features like bold, italic, underline, bullet points, etc.
User Presence: Shows the online status of other users in the document.
Document History: Keeps track of the revision history of the document.

Technologies Used
React.js: Frontend user interface and real-time rendering of document changes.
Socket.io: Enables real-time communication between the server and clients for collaborative editing.
Node.js: Server-side application and WebSocket handling.
MongoDB: Stores documents and user data.
Express.js: Backend framework to handle HTTP requests and serve the application.

Prerequisites
Node.js and npm installed on your system.
MongoDB database connection.

Getting Started
Installation
Clone the repository:
git clone https://github.com/your_username/google-docs-clone.git
cd google-docs-clone

Install the dependencies for both the client and server:
cd client
npm install

cd ../server
npm install


Configure MongoDB connection:
Create a .env file in the server directory and add your MongoDB connection URL:
MONGODB_URI=your_mongodb_connection_uri

Running the Application
Start the server:
cd server
npm devStart

Start the client:
cd client
npm start

The application will be accessible at http://localhost:3000/.

Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This project was inspired by the collaborative editing feature of Google Docs.
Special thanks to the creators and maintainers of React.js, Socket.io, Node.js, and MongoDB for providing powerful and flexible tools for building web applications.
