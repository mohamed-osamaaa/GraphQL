

https://github.com/user-attachments/assets/00c00034-345c-4b44-81d4-678dbae72797

# GraphQL

A full-stack MERN project utilizing Vite and a GraphQL API for efficient project and client management. This application provides a seamless and user-friendly interface for managing projects and clients, featuring advanced capabilities powered by GraphQL.

## Features
- **Project Management:**
  - Add new projects
  - Update existing projects
  - Delete projects
  - Fetch detailed project data

- **Client Management:**
  - Add new clients
  - Update client information
  - Delete clients
  - Fetch detailed client data

- **GraphQL API:**
  - Built with GraphQL schemas, resolvers, and mutations for robust and scalable backend solutions
  - Optimized queries to enhance performance

## Tech Stack
### Frontend:
- Vite
- React.js

### Backend:
- Node.js
- Express.js
- GraphQL

### Database:
- MongoDB

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/mohamed-osamaaa/GraphQL.git
   ```
2. Navigate to the project directory:
   ```bash
   cd GraphQL
   ```
3. Install dependencies for both client and server:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the `server` directory.
   - Add the following variables:
     ```env
     MONGO_URI=your_mongodb_connection_string
     PORT=your_preferred_server_port
     ```
5. Start the development servers:
   ```bash
   cd server
   npm run dev
   cd ../client
   npm run dev
   ```

## Usage
1. Access the application in your browser at `http://localhost:<frontend_port>`.
2. Use the GraphQL Playground at `http://localhost:<backend_port>/graphql` to explore and test the API.

## Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.
