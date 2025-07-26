# 📚 Faculty Feedback System
A web-based platform for collecting and managing student feedback about faculty, with distinct roles for HODs, Teachers, and Students.

- 👥 User Roles & Flow
🧑‍🏫 1. HOD (Head of Department)
Logs in via secure admin panel
Registers new faculty members
Generates feedback sessions/links for students
Views feedback summaries per faculty

- 👨‍🎓 2. Student
Opens session link or logs in to provide feedback
Selects faculty and submits feedback anonymously or with student ID
Prevented from submitting multiple times per session

- 👩‍🏫 3. Faculty
Logs in to view feedback submitted by students
Can view session-wise or subject-wise feedback breakdown

- 🚀 Features
🔐 Secure login for HODs, Teachers, and Students
🧾 Feedback session management by HOD
📑 Structured feedback form with multiple criteria (e.g., teaching, clarity, interaction)
📊 Feedback analytics per faculty (average scores, comments)
🔄 Prevent duplicate feedback submissions by students
🧠 Easy-to-use UI

- 🛠️ Tech Stack
Frontend: HTML, CSS
Backend: Node.js, Express.js
Database: MongoDB (via Mongoose)
Session Management: express-session or JWT (your choice)

- 📁 Folder Structure
Faculty_Feedback_System/
│
├── node_modules/         # Dependencies
├── public/               # Static files (CSS, JS, assets)
├── views/                # HTML or EJS templates
├── routes/               # Route controllers for each role
├── models/               # Mongoose schemas (User, Feedback, Session)
├── index.js              # App entry point
├── package.json
├── package-lock.json
└── README.md

- ⚙️ How to Run Locally
Clone the Repository
- git clone https://github.com/NakkaAnanthalakshmi/Faculty_Feedback_System.git
- cd Faculty_Feedback_System
Install Dependencies
- npm install
Run the Server
- node index.js
Open in browser:
- http://localhost:3000
✅ MongoDB should be running locally or connected via cloud (MongoDB Atlas).
