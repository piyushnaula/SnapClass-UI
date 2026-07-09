# SnapClass - Landing Page

This is the marketing and landing page frontend for the SnapClass AI Attendance System. It provides an overview of the features, teacher/student journeys, and technology stack, redirecting users to the main Streamlit application.

## Features
- Responsive and modern UI design.
- Detailed breakdown of features (FaceID, VoiceID).
- Step-by-step walkthroughs for teachers and students.
- Call-to-action buttons linking to the main application.

## Tech Stack
- **Backend Framework**: FastAPI (Python)
- **Frontend**: HTML5, Vanilla CSS, JS
- **Deployment Strategy**: Ready for Vercel deployment (`vercel.json` included).

## How to Run Locally

### Prerequisites
- Python 3.8+

### Setup Steps

1. **Navigate to the landing page directory**
   ```bash
   cd ai-attendance-project-landing-main
   ```

2. **Install Dependencies**
   It's recommended to use a virtual environment.
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**
   ```bash
   uvicorn app:app --port 5002 --reload
   ```
   The app will start at `http://localhost:5002`.

## Connecting with the Main App
The landing page contains hardcoded links to the Streamlit application. If you are running both locally, you may want to update the `href` attributes in `templates/index.html` to point to `http://localhost:8501`.