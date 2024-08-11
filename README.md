# SmartBot

SmartBot is a smart chatbot application developed using the MERN stack and integrated with the Gemini API. It offers a secure and interactive chat experience with real-time communication and OTP authentication for user verification.

## Features

- **Real-Time Chat**: Provides instant messaging functionality with an intuitive user interface.
- **Secure OTP Authentication**: Ensures user security with one-time password (OTP) verification.
- **Gemini API Integration**: Utilizes the Gemini API for generating intelligent responses.
- **Responsive Design**: Mobile-friendly and accessible interface with dynamic sidebars and loading indicators.
- **API Testing**: Validated endpoints using Thunderclient for robust backend integration.

## Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: OTP-based user verification
- **API**: Gemini API
- **Tools**: Thunderclient for API testing

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/jayasampreethreddy/SmartBot.git
    ```

2. Navigate to the project directory:
    ```bash
    cd SmartBot
    ```

3. Install dependencies for both frontend and backend:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

4. Create a `.env` file in the server directory with the following variables:
    ```env
    PORT=5000
    Db_url=your_mongodb_connection_string
    Gmail=your_email
    Password=your_email_password
    Activation_sec=your_activation_secret
    Jwt_sec=your_jwt_secret
    ```

5. Start the server:
    ```bash
    cd server
    npm start
    ```

6. Start the client:
    ```bash
    cd ../client
    npm start
    ```

## Usage

- **Login**: Use your email to log in and receive an OTP for authentication.
- **Chat**: Interact with the chatbot and receive intelligent responses based on your input.
- **Logout**: Securely log out of your account.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## Contact

For any inquiries, please contact kondejayasampreethreddy@gmail.com.
