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

By Austin Hurst