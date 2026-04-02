# Sprint 1 Goal (1 Week)

- Deliver a working system with:
- User Authentication
- Resource Upload/Download
- Basic Q&A (Post Question)

## Tech Stack

- Backend: FastAPI/Node.js
- Frontend: React
- Database: Postgresql
- Auth: JWT

---

# Sprint 1 Features → Tasks Breakdown

## 1. Authentication Module

- Goal:

* Users can register and log in

---

### Backend Tasks (Node.js)

1.1 Create User schema
1.2 Create user validation model
1.3 Password Hashing
1.4 JWT Token Logic
1.5 API Endpoints

- | Register | POST /auth/register |
- | Login | POST /auth/login |

---

### Frontend Tasks

- Create Login Page
- Create Register Page
- Store JWT in localStorage

---

## 2. Resource Sharing Module

- Goal:

* Upload and download course materials

### Backend Tasks

2.1 Resource Model
2.2 | File Upload Endpoint | POST /resources/upload |
2.3 | Get Resources | GET /resources |
2.4 | Download Resource | GET /resources/{id} |

### Frontend Tasks

- Upload button (teacher role)
- Resource list page
- Download button

## 3. Q&A Module (Basic Version)

- Goal:

* Students can ask questions

### Backend Tasks

3.1 Create a Question Model
3.2 Endpoints
| Create Question | POST /questions |
|Get All Questions | GET /questions |

### Frontend Tasks

- Input field (ask question)
- Display list of questions

## 4. Testing Tasks

- Backend

* Test register/login
* Test upload/download
* Test question creation

- Manual Testing Checklist:

* Can user register?
* Can login return token?
* Can upload file?
* Can view resources?
* Can post question?

---
