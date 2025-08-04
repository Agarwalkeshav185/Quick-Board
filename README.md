# QuickBoard - Smart Train Ticketing System

QuickBoard is a modern, full-stack web application designed to streamline the train ticket booking process. It integrates a machine learning model for crowd prediction and a user-friendly interface to provide a seamless experience for travelers.

## Features

- **User Authentication:** Secure user registration and login.
- **Train Search:** Search for trains between stations.
- **Booking System:** Book train tickets with ease.
- **Ticket Cancellation:** Cancel bookings with a specified reason.
- **Real-time Crowd Prediction:** ML-powered prediction to estimate crowd levels at stations.
- **Route Suggestions:** Intelligent route suggestions for travelers.
- **Emergency Notifications:** A system for sending out emergency alerts.
- **User Dashboard:** View booking history and manage profile.

## Tech Stack

- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Machine Learning:** Python, Flask, Scikit-learn

## Project Structure

The project is organized into three main directories:
- `frontend/`: Contains the React.js client-side application.
- `backend/`: Contains the Node.js/Express.js server-side application.
- `ml/`: Contains the Python/Flask machine learning model and API.

## Getting Started

### Prerequisites

- Node.js and npm
- Python and pip
- MongoDB

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Agarwalkeshav185/Quick-Board.git
    cd QuickBoard-main/QuickBoard
    ```

2.  **Backend Setup:**
    ```bash
    cd backend
    npm install
    # Create a .env file and add your MongoDB connection string and other environment variables
    # MONGO_URI=your_mongodb_uri
    # JWT_SECRET=your_jwt_secret
    npm start
    ```

3.  **Frontend Setup:**
    ```bash
    cd ../frontend
    npm install
    npm start
    ```
    The React app will be running on `http://localhost:3000`.

4.  **Machine Learning API Setup:**
    ```bash
    cd ../ml
    pip install -r requirements.txt
    python app.py
    ```
    The Flask API will be running on `http://localhost:5000`.


## Usage

Once all the services are running, you can open your browser and navigate to `http://localhost:3000` to use the QuickBoard application.

- Register for a new account or log in.
- Search for trains, view details, and book tickets.
- Check the dashboard for your booking history.
- Cancel a booking if needed.

## Future Scope

- Integration with real-time train tracking APIs.
- Mobile application for iOS and Android.
- Enhanced prediction models for delays and pricing.
- Support for multiple payment gateways.

---