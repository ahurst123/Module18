# Module18
Social Network API
Description
This project is a backend API for a social network web application where users can share their thoughts, react to friends' thoughts, and manage a friend list. The API is built using Express.js for routing, MongoDB as the database, and Mongoose as the ODM (Object Data Modeling). This application handles large amounts of unstructured data efficiently, making it suitable for social networking platforms.

Table of Contents
Installation
Usage
API Endpoints
Technologies
License
Walkthrough Video
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/social-network-api.git
Navigate to the project directory:

bash
Copy code
cd social-network-api
Install the necessary dependencies:

bash
Copy code
npm install
Create a .env file in the root directory and add your MongoDB URI:

bash
Copy code
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/socialNetworkDB?retryWrites=true&w=majority
Start the server:

bash
Copy code
node server.js
Usage
Once the server is running, you can use API clients like Insomnia or Postman to interact with the API. The API provides routes to manage users, thoughts, reactions, and friends.

API Endpoints
Users
GET /api/users - Get all users
GET /api/users/:userId - Get a single user by ID
POST /api/users - Create a new user
PUT /api/users/:userId - Update a user by ID
DELETE /api/users/:userId - Delete a user by ID
POST /api/users/:userId/friends/:friendId - Add a friend to a user's friend list
DELETE /api/users/:userId/friends/:friendId - Remove a friend from a user's friend list
Thoughts
GET /api/thoughts - Get all thoughts
GET /api/thoughts/:thoughtId - Get a single thought by ID
POST /api/thoughts - Create a new thought
PUT /api/thoughts/:thoughtId - Update a thought by ID
DELETE /api/thoughts/:thoughtId - Delete a thought by ID
POST /api/thoughts/:thoughtId/reactions - Add a reaction to a thought
DELETE /api/thoughts/:thoughtId/reactions/:reactionId - Remove a reaction from a thought
Technologies
Node.js: JavaScript runtime for building server-side applications
Express.js: Web application framework for Node.js
MongoDB: NoSQL database for storing unstructured data
Mongoose: ODM for MongoDB and Node.js
dotenv: Module for loading environment variables from a .env file
License
This project is licensed under the MIT License.

Walkthrough Video
A walkthrough video demonstrating the API's functionality can be found here.
