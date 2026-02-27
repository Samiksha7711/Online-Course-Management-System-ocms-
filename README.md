# Online-Course-Management-System-ocms-
Online Course Management System (OCMS) is a Django REST–based LMS with JWT authentication, PostgreSQL, and Redis caching. Students can enroll in courses, instructors manage content, and admins view analytics. Frontend built using HTML, CSS, and JavaScript. Secure, fast, and fully modular.

# Online Course Management System (OCMS)

OCMS is a full-stack Learning Management System built using Django REST Framework, PostgreSQL, JWT Authentication, and a clean HTML/CSS/JavaScript frontend.  
It allows students to enroll in courses, instructors to manage content, and admins to view analytics.

---

## Features

### Student Features
- Login using JWT Authentication  
- View available courses  
- Enroll in courses  
- Access enrolled content  

### Instructor Features
- Create and manage courses  
- Add price, levels, and categories  
- Publish or unpublish courses  

### Admin Features
- Dashboard with platform analytics  
- View total users, courses, enrollments  
- Manage roles and permissions  

---

## Tech Stack

### Backend
- Django 6  
- Django REST Framework  
- PostgreSQL  
- Redis caching  
- Simple JWT  

### Frontend
- HTML5  
- CSS3  
- Vanilla JavaScript  

---

## Project Structure

OCMS/
│── backend/
│ ├── accounts/
│ ├── courses/
│ ├── enrollments/
│ ├── reviews/
│ ├── ocms/ (main project)
│ └── manage.py
│
│── frontend/
│ ├── login.html
│ ├── courses.html
│ ├── style.css
│ └── main.js





### 7. Run Frontend  
Open `frontend/login.html` in browser.

---

## 🧪 API Endpoints

### Auth
| Method | Endpoint              | Description |
|--------|-----------------------|-------------|
| POST   | /api/auth/login/      | Login       |
| POST   | /api/auth/register/   | Register    |

### Courses
| Method | Endpoint          | Description |
|--------|-------------------|-------------|
| GET    | /api/courses/     | Get courses |
| POST   | /api/instructor/  | Add course  |

### Enrollments
| Method | Endpoint                  | Description      |
|--------|---------------------------|------------------|
| POST   | /api/enrollments/enroll/ | Enroll in course |

---

## 🧑‍💻 Author  
**Samiksha Pilaniya**  
Passionate about backend development, APIs, and full-stack learning systems.

---

## ⭐ Show Your Support  
If you like this project, consider giving it a **⭐ star on GitHub**!
