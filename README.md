# 🌞 ApricusEdu

[![Video Demo](https://img.shields.io/badge/Watch-Demo-red?logo=youtube)](https://youtu.be/0jZHsjSpJZg)

**ApricusEdu** (from *apricus*, Latin for “full of sunlight”) is a free educational platform that makes learning more accessible, intuitive, and joyful. Our goal is to help struggling students understand school concepts deeply — not just memorize, but truly *get it*.

---

##  Features

-  Explore homepage, team, FAQ, and feedback without registration
-  Sample educational videos for each grade and subject
-  Signup/login with form validation and error messages
-  Smooth page transitions using Flask routing and JavaScript
-  Auto-rotating and manually controllable feedback section
-  SQL database for registered users
-  Azerbaijani-language math content (grades 6–11)

---

##  How It Works

- Users land on a homepage with our mission in two lines.
- They can explore public pages: **Courses**, **Team**, **FAQ**, and **Feedbacks**.
- Clicking on **Courses** opens a dropdown of subjects → users choose one and see sample videos by grade.
- Logging in unlocks access to more personalized course pages with full lecture access.
- Our login/signup forms include real-time validation and helpful error messages, built with Flask.
- The feedback carousel uses Bootstrap for clean transitions and manual control arrows.
- Footer includes links for future social media and contact email.

---

##  Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** Flask (Python)
- **Database:** SQLite (via SQLAlchemy)
- **Sessions:** Flask-Session

---

##  Team

ApricusEdu was built by two developers who both worked on the frontend and the backend:

- **Javanshir Ismayilzada** – [GitHub](https://github.com/javanshirismayilzada)
- **Javad Ismayilzada** – [GitHub](https://github.com/Javad-cs)

##  Project Structure

```
ApricusEdu/
├── app.py
├── project.db
├── requirements.txt
├── static/
│   ├── styles.css
│   ├── images/
│   └── scripts.js
├── templates/
│   ├── layout.html
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── staff.html
│   ├── faq.html
│   ├── feedbacks.html
│   ├── course6.html
│   ├── course7.html
│   ├── course8.html
│   ├── course9.html
│   ├── course10.html
│   ├── course11.html
│   ├── logindex.html
│   ├── logcourses.html
│   └── logfaq.html
└── flask_session/
```
##  Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/Javad-cs/ApricusEdu.git
cd ApricusEdu

# 2. Set up virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
flask run
```
