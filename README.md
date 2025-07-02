# MERN Feedback Collector

A simple MERN stack application where students can submit their names and comments as feedback. All feedback is displayed on the page and stored in MongoDB.

## Features
- Submit feedback (name, message)
- View all submitted feedback
- Data stored in MongoDB

## Project Structure
```
/fwdlabfinal
  /backend
    server.js
    /models
      Feedback.js
  /frontend
    /src
      App.js
      FeedbackForm.js
      FeedbackList.js
      index.js
```

## Getting Started

### Prerequisites
- Node.js
- npm
- MongoDB (local or Atlas)

### Setup

#### Backend
1. `cd backend`
2. `npm install`
3. Create a `.env` file with your MongoDB URI:
   ```
   MONGODB_URI=your_mongodb_connection_string
   ```
4. `npm start`

#### Frontend
1. `cd frontend`
2. `npm install`
3. `npm start`

The frontend runs on `localhost:3000` and the backend on `localhost:5000` by default. 
