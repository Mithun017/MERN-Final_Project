# Virtual Classroom

## Description
The Virtual Classroom is a web application designed to facilitate online learning and collaboration. It includes features such as video conferencing, chat functionality, assignment management, and emotion detection using machine learning.

## Technologies Used
- **Frontend**: React, Vite, Bootstrap, Framer Motion
- **Backend**: Node.js, Express, MongoDB, Mongoose, Flask (for speed test and emotion detection)
- **Machine Learning**: TensorFlow/Keras for emotion detection

## Features
- User authentication (signup and login)
- Class and assignment management
- Real-time chat functionality
- Video conferencing capabilities
- Emotion detection from video feed
- Speed test functionality

## Installation

### Prerequisites
- Node.js (v14.x or higher)
- MongoDB (for the backend)
- Python (for the Flask server)
- TensorFlow/Keras (for the emotion detection model)

### Clone the Repository

### Setup and Starting the Application

#### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd Back_end
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the MongoDB server (if not already running).
4. Run the backend server:
   ```bash
   node server.js
   ```
5. The backend API will be available at `http://localhost:1234`.

#### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd Front_endT/virtual_classroom
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to `http://localhost:5173` to access the frontend.

## Usage
- Use the frontend to interact with the application, including signing up, logging in, and accessing classes.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Express](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [Flask](https://flask.palletsprojects.com/)
- [TensorFlow](https://www.tensorflow.org/)
