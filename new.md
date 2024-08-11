SmartChat Bot
SmartChat Bot is a smart chatbot application developed using the MERN stack and integrated with the Gemini API. It offers a secure and interactive chat experience with real-time communication and OTP authentication for user verification.

Features
Real-Time Chat: Provides instant messaging functionality with an intuitive user interface.
Secure OTP Authentication: Ensures user security with one-time password (OTP) verification.
Gemini API Integration: Utilizes the Gemini API for generating intelligent responses.
Responsive Design: Mobile-friendly and accessible interface with dynamic sidebars and loading indicators.
API Testing: Validated endpoints using Thunderclient for robust backend integration.
Technologies Used
Frontend: React, Tailwind CSS
Backend: Node.js, Express
Database: MongoDB
Authentication: OTP-based user verification
API: Gemini API
Tools: Thunderclient for API testing
Installation
Clone the Repository
Bash
git clone https://github.com/yourusername/SmartChat-Bot.git
Use code with caution.

Navigate to the Project Directory
Bash
cd SmartChat-Bot
Use code with caution.

Install Dependencies
Frontend:
Bash
cd client
npm install
Use code with caution.

Backend:
Bash
cd ../server
npm install
Use code with caution.

Create Environment Variables Create a .env file in the server directory with the following variables:
Code snippet
PORT=5000
Db_url=your_mongodb_connection_string
Gmail=your_email
Password=your_email_password
Activation_sec=your_activation_secret
Jwt_sec=your_jwt_secret
Use code with caution.

Start the Server
Bash
cd server
npm start
Use code with caution.

Start the Client
Bash
cd ../client
npm start
Use code with caution.

Deployment
Build the Frontend
Bash
cd client
npm run build
Use code with caution.

Deploy the Backend
Choose a hosting service (Heroku, AWS, DigitalOcean, etc.).
Upload the server directory, including the .env file.
Configure environment variables on the hosting service.
Deploy the Frontend
Choose a hosting service (Netlify, Vercel, GitHub Pages, etc.).
Upload the build directory.
Configure the frontend to point to the backend API.
Update Environment Variables Update environment variables on the hosting services if necessary.
Test the Deployment Ensure the application works correctly on the deployed environment.
Usage
Open http://localhost:3000 in your browser.
Register or log in.
Verify your account using OTP.
Start chatting with the bot.
Contributing
Fork the repository.
Create a new branch.
Commit changes and push to your fork.
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Gemini API: For intelligent response generation.
React: For building the user interface.
Tailwind CSS: For styling the application.
MongoDB: For database management.
Node.js: For server-side development.
Express: For handling HTTP requests.
Thunderclient: For API testing.