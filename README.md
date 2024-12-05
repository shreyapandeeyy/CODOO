# LitCode 🔥

LitCode is a competitive 1v1 coding platform where developers can challenge each other to solve algorithmic problems in real-time. Think of it as a multiplayer version of LeetCode where you can directly compete against other programmers!

## 📺 Quick Demo

[![LitCode Demo](https://img.youtube.com/vi/Hg4UC5cIdhc/0.jpg)](https://www.youtube.com/watch?v=Hg4UC5cIdhc)

*Watch how LitCode brings competitive programming to life! See real-time battles between coders competing to solve algorithmic challenges.*

## 🎮 How It Works

1. Queue up for a match by selecting your preferred problem category:
   - Graph Problems
   - Tree Traversals
   - Array Manipulations
   - And more!

2. Get matched with another player in your skill range
3. Race to solve the coding challenge
4. First person to pass all test cases wins! 

## 🚀 Features

- Real-time 1v1 coding battles
- Category-based matchmaking system
- Live opponent progress tracking
- Comprehensive test case validation
- Skill-based rating system
- Performance analytics and history
- Custom judge system for code evaluation

## 🛠️ Tech Stack

### Frontend
- **Next.js** with TypeScript for robust client-side application
- Real-time updates using WebSocket connections
- Modern, responsive UI design
- Code editor with syntax highlighting

### Backend
- **Flask** REST API server
- **MongoDB** for storing:
  - User profiles and authentication
  - Coding problems and test cases
  - Match history and statistics
- **JudgeIO** API integration for code compilation and execution
- Secure LAN deployment within McGill University network

## 📝 Setup Instructions

### Prerequisites

- Node.js (v14.x or later)
- npm (v6.x or later) or yarn
- Python (v3.8 or later)
- MongoDB (local or cloud instance)
- RapidAPI account for Judge0 API key

### Step-by-Step Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shreyapandeeyy/CODOO.git
   cd CODOO
   ```

2. **Install dependencies:**
   ```bash
   # For the frontend
   cd frontend
   npm install
   # or
   yarn install

   # For the backend
   cd ../backend
   pip install -r requirements.txt
   ```

3. **Configure environment variables:**
   - Create a `.env` file in the root directory of both frontend and backend.
   - Use the provided `.env.example` file as a template.

4. **Run the application:**
   ```bash
   # Start the frontend
   cd frontend
   npm run dev
   # or
   yarn dev

   # Start the backend
   cd ../backend
   python app.py
   ```

5. **Access the application:**
   - Open your browser and navigate to `http://localhost:3000` for the frontend.
   - The backend server should be running on `http://localhost:5000`.

### Environment Variables

Make sure to set the following environment variables in your `.env` files:

#### Frontend `.env` file:
```
NEXT_PUBLIC_JUDGE0_API_KEY=your_judge0_api_key
NEXT_PUBLIC_MONGO_DB_KEY=your_mongo_db_key
NEXT_PUBLIC_SIGNING_SECRET=your_signing_secret
```

#### Backend `.env` file:
```
JUDGE0_API_KEY=your_judge0_api_key
MONGO_DB_KEY=your_mongo_db_key
SIGNING_SECRET=your_signing_secret
```

## 📚 Additional Information

### Purpose

LitCode aims to provide a fun and competitive environment for developers to improve their coding skills. By competing against others, developers can learn new techniques, improve their problem-solving abilities, and gain confidence in their coding skills.

### Features

- **Real-time Battles:** Engage in real-time coding battles with other developers.
- **Matchmaking System:** Get matched with opponents of similar skill levels.
- **Progress Tracking:** Track your progress and see how you stack up against your opponents.
- **Comprehensive Test Cases:** Ensure your code is robust and handles various edge cases.
- **Skill-based Rating System:** Improve your rating as you win more matches.
- **Performance Analytics:** Analyze your performance and identify areas for improvement.
- **Custom Judge System:** Evaluate your code with a custom judge system that supports various programming languages.

### Future Enhancements

- **More Problem Categories:** Add more problem categories to provide a wider range of challenges.
- **Leaderboard:** Implement a leaderboard to showcase top performers.
- **User Profiles:** Allow users to create and customize their profiles.
- **Achievements:** Introduce achievements and badges to reward users for their accomplishments.
- **Social Features:** Enable users to connect with friends and challenge them to matches.

We hope you enjoy using LitCode and find it helpful in improving your coding skills. Happy coding!
