


# MERN Booking App

## Project Overview

- **Frontend**: React application for the user interface.
- **Backend**: Node.js and Express.js server to handle reservations.
- **Database**: MongoDB for storing reservation data.

## Getting Started

### Prerequisites

- Node.js and npm: Make sure Node.js and npm are installed on your machine.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mariangle/mern-booking-app.git
   cd mern-booking-app
   ```

2. **Install dependencies for both frontend and backend:**

   ```bash
   cd frontend
   npm install

   cd ../backend
   npm install
   ```

### Configuration

1. **Create a `.env` file in the `backend` folder and add the following configuration:**

   ```env
   PORT=4000
   FRONTEND_URL=http://localhost:5173
   MONGO_URI=your_mongodb_connection_string
   ```

   Replace `your_mongodb_connection_string` with the connection string for your MongoDB cluster.

### Running the Project

1. **Start the backend server:**

   ```bash
   cd backend
   npm run dev
   ```

   This will start the server on `http://localhost:4000`.

2. **Start the frontend application:**

   ```bash
   cd frontend
   npm start
   ```

   This will start the React development server on `http://localhost:5173`.

Now you can access the application in your web browser at `http://localhost:5173`.

## Adding Data to MongoDB

You can add data to your MongoDB cluster by making reservations through the application or manually adding data using the MongoDB Atlas dashboard.

1. **Visit your [MongoDB Atlas Dashboard](https://cloud.mongodb.com/v2/your_cluster_id#/overview).**

2. **Navigate to the "Collections" tab and select the "Reservations" collection.**

3. **Use the "Insert Document" button to manually add reservation data.**

Feel free to explore the code and customize the application to suit your needs.
```

Feel free to further customize or expand the README to include any additional details or instructions relevant to your project.
