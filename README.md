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
- [Project Repositories](#project-repositories)
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
- **Timetable Management**: Create, view, manage, and optimize class schedules.
- **Attendance Tracking**: Teachers can mark daily attendance with real-time notifications and comprehensive reporting for teachers and parents.
- **Performance Analytics**: Track student progress with detailed analytics, grade management, and personalized learning insights.
- **AI Query Engine**: Natural language queries to analyze school data and get actionable recommendations for improved outcomes.
  - Examples:
    - “Who is absent today?”
    - “When is the next Science class?”
    - “Top students in Math this term.”

---

## 🏗 Architecture

```text
                  +----------------------+
                  |   User Interface     |
                  |      (Frontend)      |
                  +----------+-----------+
                             |
                             v
                  +----------------------+
                  | Application Logic    |
                  |      (Backend)       |
                  +----------+-----------+
                             |
      +----------------------+-----------------------+
      |                      |                       |
      v                      v                       v
+-------------+     +------------------+     +----------------------+
|   Database  |     | AI Query Engine  |     | Authentication &     |
|    Layer    |     |  (NLP + Reports) |     |     Security         |
+-------------+     +------------------+     +----------------------+

                             |
                             v
                  +----------------------+
                  | Deployment &         |
                  | Infrastructure       |
                  +----------------------+


---

## ⚙️ Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript, React
- **Backend**: Python (flask)
- **Database**: MySQL
- **AI Integration**: Hugging Face API (Language Model for Natural-Language Queries)
- **Development Tools**: Lovable
- **Hosting**: bolt.new
- **Monetization**: IntaSend

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
| Table       | Columns                                                              |
|-------------|----------------------------------------------------------------------|
| Users       | id, name, role, email, password                                      |
| Student     | id, first_name, last_name, class, roll_no                            |
| Teacher     | id, first_name, last_name, subject                                   |
| timetables  | id, class, day_of_week, start_time, end_time, subject, teacher_id    |
| attendance  | id, student_id, status, note                                         |
| Performance | id, student_id, subject, term, score, max_score                      |

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

## 🚀 Future Improvements

Advanced analytics dashboards.

AI-powered grading and performance prediction.

Multi-language support.

Mobile app version.


---

## 🔗 Project Repositories
- [Frontend Repository](https://github.com/SmartEd-Solutions/backend.git)
- [Backend Repository](https://github.com/SmartEd-Solutions/NeoLearn-Frontend.git)
- [API Repository](https://github.com/SmartEd-Solutions/API.git)

---

## 👨‍💻 Team

[Teammate 1] – Frontend Developer

[Obuye Emmanuel chukwuemeke] – Backend Developer & Database

[Eunice Fagbemide] – AI Integration

[Teammate 4] – Testing

[Eunice Ohilebo] – Documentation & Pitch



