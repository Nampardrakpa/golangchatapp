# Real-Time Chat App

Welcome to the Real-Time Chat App! This application allows users to create accounts, update account details, delete accounts, authenticate users, create and join chat rooms, and engage in real-time chatting without the need to refresh the page. The project is built using Next.js, TypeScript, MongoDB with migrations, Tailwind CSS, and Golang with WebSockets, concurrency, and tokenization.

### Features
Account Management:

Create an account with unique credentials.
Update account details, such as username and profile information.
Delete an account if needed.
User Authentication:

Secure user authentication and authorization mechanisms.
JWT (JSON Web Token) based authentication for enhanced security.
Chat Room Functionality:

Create new chat rooms.
Join existing chat rooms.
Real-time updates on new messages and participants.
Real-Time Messaging:

Seamlessly chat with other users in real-time.
Messages appear instantly without the need to refresh the page.
WebSockets ensure efficient and timely communication.
Technologies Used
Frontend:

Next.js: A React framework for building user interfaces.
TypeScript: Adds static typing to JavaScript to improve code quality and development experience.
Tailwind CSS: A utility-first CSS framework for designing responsive and modern UIs.
Backend:

Golang: A powerful and efficient programming language used for building the server-side logic.
WebSockets: Enables real-time communication between the server and clients.
Concurrency: Leverages Go's concurrency primitives to handle multiple client connections efficiently.
Tokenization: Secure user authentication using JSON Web Tokens.
Database:

MongoDB: A NoSQL database for storing user accounts, chat rooms, and messages.
Migrations: Manage and version-control the database schema.
Getting Started

### Clone the repository:
git clone https://github.com/your-username/real-time-chat-app.git

### Set up the client:
'''bash
cd client
npm install
npm run dev

### Set up the server:
'''bash
cd server
go run main.go

### Access the application:
Open your browser and navigate to http://localhost:3000.

### Contributions
Contributions to this project are welcome! If you find any bugs or want to add new features, please feel free to create issues or pull requests.

### This is a Golang chat App that I built.
This was built based on david hwang's own golang chat app.

https://www.youtube.com/watch?v=W9SuX9c40s8

https://www.youtube.com/watch?v=760GKM7s_5Y

https://www.youtube.com/watch?v=zGSqG0vkBxo
