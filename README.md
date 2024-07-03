# MindCrew: AI-Driven Mental Health Companion

The AI Mental Health Assistant is a web application designed to provide mental health support through various features, including mood tracking, personalized recommendations, achievements, resources, chat support, virtual mental health coach, and stress buster beats! The project leverages modern web technologies and machine learning to create an interactive and user-friendly platform for mental wellness.

Mood Tracker: Track your daily mood and view trends over time through graphical representations.
Recommendations: Get personalized recommendations based on your mood to improve your mental health.
Achievements: Track your progress and view your achievements.
Resources: Access a variety of mental health resources and information.
Chat Support: Get instant support and answers to your mental health queries.
Virtual Mental Health Coach: Receive personalized mental health advice and exercises.
Create Music: Generate custom music based on your preferences and mood.
Tech Stack
Frontend: HTML, CSS (Bootstrap), JavaScript
Backend: Flask (Python)
Database: SQLite
Machine Learning: Scikit-learn for mood prediction
Visualization: Chart.js for graphical representation of mood trends
Installation
Prerequisites
Python 3.x
Virtual environment (optional but recommended)
Steps
Clone the repository:


git clone https://github.com/arushi32588/AI-Mental-Health-Assistant.git
cd AI-Mental-Health-Assistant
Create a virtual environment and activate it:


python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
Install the required dependencies:

sh
Copy code
pip install -r requirements.txt
Initialize the database:

sh
Copy code
flask db init
flask db migrate -m "Initial migration"
flask db upgrade
Run the application:

sh
Copy code
flask run
Open your web browser and navigate to:

arduino
Copy code
http://127.0.0.1:5000/
Usage
Login/Register: Create an account or log in to access the features.
Dashboard: Navigate through different features from the dashboard.
Mood Tracker: Add your mood entries and visualize your mood trends.
Recommendations: Get personalized tips and activities based on your mood.
Achievements: Track your mental health progress and achievements.
Resources: Explore various mental health resources.
Chat Support: Interact with the chat support for immediate help.
Virtual Coach: Get personalized mental health advice.
Create Music: Generate music based on your mood and preferences.
Screenshots
Dashboard

Mood Tracker

Recommendations

Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements, bug fixes, or feature additions.
