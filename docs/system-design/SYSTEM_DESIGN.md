# LearnSphere – System Design

**Project:** LearnSphere – Student Learning & Course Analytics Portal

**Version:** 1.0

---

## 1. System Overview

LearnSphere is a student learning and course analytics platform that
combines a web-based learning interface with a database and analytics layer.

The system allows students to browse courses, enroll in courses, track
learning progress, complete quizzes, manage favorites, and provide reviews.

Administrators and instructors can monitor course and student activity.

The collected data is analyzed using SQL and Python and visualized through
Power BI dashboards.

---

## 2. System Architecture

The system consists of the following layers:

### Presentation Layer

- HTML
- CSS
- Bootstrap
- JavaScript

Responsible for displaying the user interface.

### Application Layer

Responsible for:

- Course management
- Enrollment
- Progress tracking
- Quiz management
- Reviews
- User operations

### Database Layer

MySQL stores:

- Users
- Students
- Instructors
- Courses
- Categories
- Lessons
- Enrollments
- Favorites
- Progress
- Quizzes
- Quiz attempts
- Reviews

### Analytics Layer

SQL and Python are used to analyze stored data.

### Visualization Layer

Power BI is used to create:

- KPI dashboards
- Course analytics
- Student analytics
- Category analytics
- Instructor analytics
- Learning trends
- Business insights

---

## 3. System Flow

User
↓
Web Interface
↓
Application Functions
↓
MySQL Database
↓
SQL / Python Analysis
↓
Power BI
↓
Dashboards & Reports

---

## 4. User Roles

### Student

- Browse courses
- Search courses
- Filter courses
- View course details
- Enroll
- Add favorites
- Complete lessons
- Track progress
- Take quizzes
- View scores
- Submit reviews
- View dashboard

### Instructor

- View assigned courses
- Manage course information
- Manage lessons
- View enrolled students
- View course performance

### Admin

- Manage students
- Manage instructors
- Manage courses
- Manage categories
- Monitor enrollments
- View analytics
- Generate reports

---

## 5. Use Case Overview

### Student Use Cases

- Login
- Browse Courses
- Search Courses
- Filter Courses
- View Course
- Enroll
- Add Favorite
- Learn Lessons
- Track Progress
- Take Quiz
- View Quiz Score
- Submit Review
- View Dashboard

### Instructor Use Cases

- Login
- View Courses
- Manage Courses
- Manage Lessons
- View Students
- View Course Performance

### Admin Use Cases

- Login
- Manage Users
- Manage Courses
- Manage Categories
- Manage Instructors
- Monitor Enrollments
- View Analytics
- Generate Reports

---

## 6. Data Flow

Student Activity
↓
MySQL Database
↓
SQL Queries
↓
Python Data Analysis
↓
Cleaned / Processed Data
↓
Power BI
↓
Dashboard
↓
Insights & Reports

---

## 7. Analytics Flow

The analytics component converts application data into useful insights.

Examples:

- Course popularity
- Course completion rate
- Student engagement
- Quiz performance
- Category performance
- Instructor performance
- Enrollment trends
- Course ratings

---

## 8. Major System Modules

1. User Management
2. Student Management
3. Instructor Management
4. Course Management
5. Category Management
6. Enrollment
7. Favorites
8. Learning Progress
9. Quiz & Assessment
10. Reviews & Ratings
11. Reports
12. Analytics

---

## 9. System Constraints

- Two-person development team
- Free development tools
- No paid APIs
- No live external integrations
- No cloud infrastructure required
- Synthetic/sample data
- Medium-scale academic project

---

## 10. Future Enhancements

- Mobile application
- Cloud deployment
- AI course recommendation
- AI learning assistant
- Live video learning
- Real-time notifications
- Advanced authentication
- Payment integration
- External APIs
