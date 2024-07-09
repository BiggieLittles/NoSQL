#Social Network API
Welcome to the repository for the Social Network API! This project is a backend application for a social networking platform, built using Express and Mongoose. It provides RESTful API endpoints for user authentication, profile management, posting updates, and interacting with other users.

Features
User Authentication: Secure user registration and login functionality.
Profile Management: Users can create and update their profiles.
Post Management: Users can create, read, update, and delete posts.
Friendship Management: Users can send, accept, and remove friend requests.
Like and Comment: Users can like and comment on posts.
API Documentation: Detailed API documentation for easy integration.
Technologies Used
Backend:
Framework: Express.js
Database: MongoDB
ORM: Mongoose
Tools & Platforms:
Version Control: Git
API Documentation: Insomnia
Getting Started
Prerequisites
Make sure you have the following installed on your local machine:

Node.js
MongoDB
Installation
Clone the repository:

sh
Copy code
git clone https://github.com/biggielittles/NoSQL.git
cd social-network-api
Install dependencies:

sh
Copy code
npm install
Set up environment variables:
Create a .env file in the root directory and add the following:

makefile
Copy code
MONGODB_URI=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>
Start the application:

sh
Copy code
npm start
Access the API documentation:
Open your browser and go to http://localhost:3000/api-docs

Project Structure
bash
Copy code
social-network-api/

API Endpoints
Authentication
POST /api/auth/register: Register a new user
POST /api/auth/login: Login a user
Profile
GET /api/profiles/
: Get user profile
PUT /api/profiles/
: Update user profile
Posts
POST /api/posts: Create a new post
GET /api/posts: Get all posts
GET /api/posts/
: Get a single post
PUT /api/posts/
: Update a post
DELETE /api/posts/
: Delete a post
Friendships
POST /api/friends/request/
: Send a friend request
POST /api/friends/accept/
: Accept a friend request
DELETE /api/friends/remove/
: Remove a friend
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
If you have any questions, feel free to contact me at homedog833@gmail.com.
