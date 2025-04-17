# Courseeker

Courseeker is a web platform that centralizes free online courses from various sources and offers personalized recommendations based on a user's learning preferences. The platform includes a progress tracking system, helping users stay organized and motivated throughout their self-learning journey.

## Features

- **Personalized Quiz**: Tailored course recommendations based on topic preferences, complexity, and learning type.
- **Course Recommendations**: Aggregates free courses from various sources, all in one place.
- **Progress Tracking**: Users can log study sessions, set tasks, and track their progress using a to-do list and timer.
- **Multiple Sources**: Although courses are currently manually populated in the database, future plans include integrating APIs from platforms like Khan Academy and AI scraping for course suggestions.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Python Flask
- **Database**: MongoDB Atlas
- **Version Control**: GitHub (for collaboration and code management)
- **Hosting**: (Add hosting details here, if applicable)

## Setup Instructions

### Prerequisites

- Node.js
- Python
- MongoDB Atlas account

### Steps to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yabai2309/educational-source-rec.git
2. **Install dependencies**:
   - For the frontend:
   ```bash
   cd frontend
   npm install
   ```
   - For the backend:
   ```bash
   cd backend
   python -m venv venv
   ```
     - Activate virtual environment through:
       - Windows: venv\Scripts\activate
       - macOS/ Linux: source venv/bin/activate
     - Install the requirement packages:
   ```bash
   pip install -r requirements.txt
    ```
3. **Run the app**:
  - For the frontend:
```bash
cd frontend
npm start
```
  - For the backend:
```bash
cd backend
python app.py
```
