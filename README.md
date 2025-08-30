# NeoLearn-school-management-system-documentation
Main documentation and links for the AI-powered school management system.


# 🏫 NeoLearn School Management System (AI-Powered)

_A smart, scalable solution for managing school operations with AI-powered insights, built for SDG 4: Quality Education._

---

## 📚 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [AI Integration](#ai-integration)
- [Prompt Engineering](#prompt-engineering)
- [Database Structure](#database-structure)
- [Screenshots](#screenshots)
- [Setup Instructions](#setup-instructions)
- [Future Improvements](#future-improvements)
- [Team](#team)

---

## ✅ Overview
Managing school operations like timetables, attendance, and performance can be time-consuming and prone to errors. Our **School Management System** automates these processes and introduces an **AI-powered query feature** that allows users to ask natural-language questions such as:

- *“Who is absent today?”*
- *“When is the next Math class?”*
- *“Show the top 3 students in Math this term.”*

This system is built to **improve efficiency and accessibility** in schools, aligning with **SDG 4: Quality Education**.

---

## 🔑 Features
- **User Management**: Admin, Teacher, Student roles with login functionality.
- **Timetable Management**: Create, view, and edit class schedules.
- **Attendance Tracking**: Teachers can mark daily attendance.
- **Performance Tracking**: Record and view exam scores.
- **AI Query Engine**:
  - Natural-language questions for instant insights.
  - Examples:
    - “Who is absent today?”
    - “When is the next Science class?”
    - “Top students in Math this term.”

---

## 🏗 Architecture

---

## ⚙️ Tech Stack
- **Frontend**: 
- **Backend**: Python (flask)
- **Database**: MySQL
- **AI**: 
- **Hosting**:
- **Pitch**:
  

---

## 🤖 AI Integration
Our AI module enables **natural-language querying**:
1. The user enters a question (e.g., “Who is absent today?”).
2. AI interprets the question.
3. The backend translates it into an SQL query.
4. Results are formatted and returned to the user.

### Example Queries:
- **Attendance**: “Who is absent today?”
- **Schedule**: “When is the next Math class?”
- **Performance**: “Show top 3 students in Science this term.”

---

## ✍️ Prompt Engineering
We used **prompt engineering** to ensure the AI gives **accurate, context-aware, and concise answers**.

### Why Prompt Engineering?
- To make the AI understand our **database structure**.
- To ensure clear and relevant responses.
- To avoid unnecessary details.

### Example Prompts:
STILL WORKING ON ARRANGING THE PROMPTS

---

## 🗄 Database Structure
| Table       | Columns                                         |
|-------------|-------------------------------------------------|
| Users       | id, name, role, email, password                |
| Roles       | id, role_name (Admin, Teacher, Student)        |
| Students    | id, user_id, class, enrollment_date            |
| Teachers    | id, user_id, subjects                          |
| Subjects    | id, name                                       |
| Classes     | id, name, teacher_id                           |
| Schedule    | id, class_id, subject_id, teacher_id, day, time|
| Attendance  | id, student_id, date, status                  |
| Performance | id, student_id, subject_id, score, exam_date  |

---

## 🖼 Screenshots
*(Add screenshots of the UI here after development.)*
- Login Page
- Dashboard
- AI Query Box

---

## 🛠 Setup Instructions
Clone the repository:
```bash
git clone <repo-url>
cd school-management-system

Install dependencies:

pip install -r requirements.txt

Run the app:

python app.py

Access in browser:

http://127.0.0.1:5000/


---

🚀 Future Improvements

Advanced analytics dashboards.

AI-powered grading and performance prediction.

Multi-language support.

Mobile app version.


---

👨‍💻 Team

[Teammate 1] – AI Integration

[Teammate 2] – Backend Developer

[Teammate 3] – Frontend Developer

[Teammate 4] – Database & Testing

[Eunice Ohilebo] – Documentation & Pitch



