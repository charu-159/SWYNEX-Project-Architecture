
# SWYNEX Task Manager

## 1. Product Idea
A web application that helps users create, organize, and track their daily tasks.

## 2. Technology Stack
- Frontend: React.js
- Backend: Node.js and Express.js
- Database: MongoDB
- API: REST API

## 3. Data Models

### User
- name
- email
- password

### Task
- title
- description
- status
- priority
- dueDate
- userId

## 4. API Routes

- POST /api/auth/register
- POST /api/auth/login
- GET /api/tasks
- POST /api/tasks
- PUT /api/tasks/:id
- DELETE /api/tasks/:id

## 5. Frontend Screens
- Login
- Register
- Dashboard
- Task List
- Add/Edit Task
- Profile

## 6. Application Flow
React Frontend → Express Backend → MongoDB Database

## 7. Security
- Hash user passwords
- Validate input data
- Protect user-specific tasks
- Use authentication for private routes

## 8. Future Improvements
- Task reminders
- Progress charts
- Calendar view
- Mobile responsive design
