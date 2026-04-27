# 💼 Full Stack Job Portal Application

A complete **full-stack job portal web application** built with **Java Spring Boot (Backend)** and **React + Vite (Frontend)**.  
It supports **secure authentication**, job browsing, filtering, saving, applying, and **role-based access** for job seekers and employers.

This project demonstrates a **real-world job marketplace experience** — from job seekers discovering and applying for jobs to employers posting jobs and managing applicants.

---

## 👨‍💻 About This Project

I built this application to simulate core job platform workflows (similar to LinkedIn or Indeed) while mastering full-stack development. The project includes:

- **Secure JWT authentication** with role-based access
- **Dynamic job listing** with search, filter, and save features
- **Complete application lifecycle** from applying to hiring decisions
- **Interactive dashboards** for both job seekers and employers
- **Real-time notifications** for application status updates

The entire codebase follows modular architecture with clean separation of concerns.

---

## 🛠️ Technology Stack

### Backend
| Technology | Purpose |
|------------|---------|
| Java 17 | Core programming language |
| Spring Boot | Application framework |
| Spring Security + JWT | Authentication & authorization |
| Hibernate (JPA) | Database ORM |
| PostgreSQL | Relational database |
| Lombok | Boilerplate code reduction |

### Frontend
| Technology | Purpose |
|------------|---------|
| React.js | UI library |
| Vite | Build tool & development server |
| Axios | HTTP client for API calls |
| Formik | Form handling & validation |
| Context API | State management |
| Plain CSS | Styling (no external frameworks) |

---

## ✨ Features Implemented

### 🔐 Authentication System
- Secure user registration & login
- JWT token-based authentication
- Role-based access control (Job Seeker / Employer)
- Protected routes and API endpoints

### 👥 Job Seeker Features
| Feature | Description |
|---------|-------------|
| Job Discovery | Browse, filter, and search jobs by title, location, and type |
| Job Details | View complete job descriptions, responsibilities, and skills |
| Save Jobs | Save/unsave jobs with instant visual feedback |
| Apply to Jobs | Submit applications with resume upload and screening questions |
| Track Applications | View saved jobs, applied jobs, and application status |
| Withdraw Applications | Cancel applications anytime |
| Profile Management | Update profile picture, resume, and personal details |
| Notifications | Receive real-time alerts for status changes |

### 🏢 Employer Features
| Feature | Description |
|---------|-------------|
| Job Posting | Create jobs with full details, skills, and screening questions |
| Job Management | Edit and delete existing job postings |
| Applicant Management | View applicants per job or across all jobs |
| Hiring Decisions | Accept/reject applicants with automatic notifications |
| Resume Review | View applicant resumes directly in browser |
| Analytics Dashboard | View statistics on jobs, applicants, acceptances, and rejections |

---

## 🎯 Project Highlights

- ✅ **60+ unique UI screens** designed and implemented from scratch
- ✅ **Production-ready REST API** with clean service-layer architecture
- ✅ **Real database integration** (PostgreSQL) with optimized relationships
- ✅ **Secure file uploads** for resumes and profile pictures
- ✅ **Real-time notification system** using efficient state management
- ✅ **Role-based access control** ensuring separate workflows
- ✅ **Fully responsive design** adaptable to all screen sizes

---

## 📸 Screenshots

### 🌐 Common Pages

#### Home Page
![HomePage](./ScreenShots/HomePage.png)
*Landing page with clear sign up/log in options*

#### Role Selection
![SelectionOptions](./ScreenShots/SelectionOptions.png)
*Users choose account type before registration*

---

### 👤 Job Seeker Flow

| Step | Screenshot | Description |
|------|------------|-------------|
| Registration | ![Register](./ScreenShots/RegisteringJobSeeker.png) | Sign up with profile picture & resume |
| Job Listing | ![Landing](./ScreenShots/LandingJobPage.png) | Browse jobs with cards and details panel |
| Pagination | ![Viewing](./ScreenShots/ViewingJobs.png) | Navigate through multiple job pages |
| Job Details | ![Selected](./ScreenShots/SelectedJobGoogle.png) | View complete job information |
| Filter by Type | ![Search Types](./ScreenShots/SearchTypes.png) | Filter jobs (Full-time, Internship, etc.) |
| Search Feature | ![Searching](./ScreenShots/SearchingForJob.png) | Find jobs by keywords |
| Job Card | ![Card](./ScreenShots/JobCard.png) | Compact job information display |
| Save Job | ![Saving](./ScreenShots/SavingGameDevJob.png) | Save jobs with visual feedback |
| My Jobs | ![My Jobs](./ScreenShots/MyJobs.png) | Track saved and applied jobs |
| Remove Saved | ![Remove](./ScreenShots/RemovingSavedJob.png) | Remove saved jobs instantly |
| Apply Process | ![Applying](./ScreenShots/ApplyingforGameDevJob.png) | Answer screening questions |
| Application View | ![Details](./ScreenShots/ApplicationDeatils.png) | View submitted application |
| Notification Popup | ![Popup](./ScreenShots/NotificationPopUp.png) | Real-time status updates |
| Notification Detail | ![Detail](./ScreenShots/NotificationCloserLook.png) | Detailed notification view |
| Bell Icon | ![Bell](./ScreenShots/NotificationFromBell.png) | Notification dropdown menu |

---

### 🏢 Employer Flow

| Step | Screenshot | Description |
|------|------------|-------------|
| Employer Signup | ![Signup](./ScreenShots/EmployerSiginUp.png) | Register with company details |
| Empty Dashboard | ![Empty](./ScreenShots/DashboardGoogle.png) | Initial state before posting jobs |
| Create Job (Step 1) | ![Create1](./ScreenShots/CreatingJob.png) | Add job title and description |
| Add Skills | ![Create2](./ScreenShots/CreatingJob4.png) | Enter required job skills |
| Success Message | ![Success](./ScreenShots/CreatingJobSucessfully.png) | Job creation confirmation |
| Job Details View | ![Details](./ScreenShots/CreatedJobDetails.png) | View with edit/delete options |
| Dashboard Populated | ![Populated](./ScreenShots/DashboardGoogleAfteraddingJobs.png) | Statistics after adding jobs |
| View Applicants | ![Applicants](./ScreenShots/ViewingApplicants.png) | List of job applicants |
| Application Details | ![App Details](./ScreenShots/ViewingApplicationDetails.png) | Detailed applicant information |
| Status Update | ![Accepted](./ScreenShots/Statuschangedtoaccepted.png) | Accept/reject with auto-notification |

---

## 📂 Project Structure

job-portal/
│
├── README.md # Project documentation
├── Full_Walkthrough.md # Complete screenshot guide
│
├── Backend/
│ └── JobPortal/ # Spring Boot application
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/ # Java source code
│ │ │ │ ├── config/ # Security & JWT config
│ │ │ │ ├── controllers/
│ │ │ │ ├── models/
│ │ │ │ ├── repositories/
│ │ │ │ └── services/
│ │ │ └── resources/ # Properties files
│ │ └── test/ # Unit tests
│ └── pom.xml # Maven dependencies
│
├── Frontend/
│ └── JobPortalFront/ # React + Vite application
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Page components
│ │ ├── context/ # Context API state
│ │ ├── services/ # API service calls
│ │ └── utils/ # Helper functions
│ └── package.json # NPM dependencies
│
└── ScreenShots/ # All application screenshots
├── HomePage.png
├── RegisteringJobSeeker.png
├── DashboardGoogle.png
└── ... (60+ screenshots)

---

## 🚀 Getting Started

### Prerequisites

- **Java 17** or higher
- **Node.js 16+** and npm
- **PostgreSQL** database
- **Git** for version control

### Backend Setup

```bash
# Navigate to backend
cd Backend/JobPortal

# Configure PostgreSQL (update application.properties)
spring.datasource.url=jdbc:postgresql://localhost:5432/jobportal_db
spring.datasource.username=your_username
spring.datasource.password=your_password

# Build and run
./mvnw clean install
./mvnw spring-boot:run
Backend runs on: http://localhost:8080


Here's your personalized README with the same tech stack (no changes), just rebranded as your project:

markdown
# 💼 Full Stack Job Portal Application

A complete **full-stack job portal web application** built with **Java Spring Boot (Backend)** and **React + Vite (Frontend)**.  
It supports **secure authentication**, job browsing, filtering, saving, applying, and **role-based access** for job seekers and employers.

This project demonstrates a **real-world job marketplace experience** — from job seekers discovering and applying for jobs to employers posting jobs and managing applicants.

---

## 👨‍💻 About This Project

I built this application to simulate core job platform workflows (similar to LinkedIn or Indeed) while mastering full-stack development. The project includes:

- **Secure JWT authentication** with role-based access
- **Dynamic job listing** with search, filter, and save features
- **Complete application lifecycle** from applying to hiring decisions
- **Interactive dashboards** for both job seekers and employers
- **Real-time notifications** for application status updates

The entire codebase follows modular architecture with clean separation of concerns.

---

## 🛠️ Technology Stack

### Backend
| Technology | Purpose |
|------------|---------|
| Java 17 | Core programming language |
| Spring Boot | Application framework |
| Spring Security + JWT | Authentication & authorization |
| Hibernate (JPA) | Database ORM |
| PostgreSQL | Relational database |
| Lombok | Boilerplate code reduction |

### Frontend
| Technology | Purpose |
|------------|---------|
| React.js | UI library |
| Vite | Build tool & development server |
| Axios | HTTP client for API calls |
| Formik | Form handling & validation |
| Context API | State management |
| Plain CSS | Styling (no external frameworks) |

---

## ✨ Features Implemented

### 🔐 Authentication System
- Secure user registration & login
- JWT token-based authentication
- Role-based access control (Job Seeker / Employer)
- Protected routes and API endpoints

### 👥 Job Seeker Features
| Feature | Description |
|---------|-------------|
| Job Discovery | Browse, filter, and search jobs by title, location, and type |
| Job Details | View complete job descriptions, responsibilities, and skills |
| Save Jobs | Save/unsave jobs with instant visual feedback |
| Apply to Jobs | Submit applications with resume upload and screening questions |
| Track Applications | View saved jobs, applied jobs, and application status |
| Withdraw Applications | Cancel applications anytime |
| Profile Management | Update profile picture, resume, and personal details |
| Notifications | Receive real-time alerts for status changes |

### 🏢 Employer Features
| Feature | Description |
|---------|-------------|
| Job Posting | Create jobs with full details, skills, and screening questions |
| Job Management | Edit and delete existing job postings |
| Applicant Management | View applicants per job or across all jobs |
| Hiring Decisions | Accept/reject applicants with automatic notifications |
| Resume Review | View applicant resumes directly in browser |
| Analytics Dashboard | View statistics on jobs, applicants, acceptances, and rejections |

---

## 🎯 Project Highlights

- ✅ **60+ unique UI screens** designed and implemented from scratch
- ✅ **Production-ready REST API** with clean service-layer architecture
- ✅ **Real database integration** (PostgreSQL) with optimized relationships
- ✅ **Secure file uploads** for resumes and profile pictures
- ✅ **Real-time notification system** using efficient state management
- ✅ **Role-based access control** ensuring separate workflows
- ✅ **Fully responsive design** adaptable to all screen sizes

---

## 📸 Screenshots

### 🌐 Common Pages

#### Home Page
![HomePage](./ScreenShots/HomePage.png)
*Landing page with clear sign up/log in options*

#### Role Selection
![SelectionOptions](./ScreenShots/SelectionOptions.png)
*Users choose account type before registration*

---

### 👤 Job Seeker Flow

| Step | Screenshot | Description |
|------|------------|-------------|
| Registration | ![Register](./ScreenShots/RegisteringJobSeeker.png) | Sign up with profile picture & resume |
| Job Listing | ![Landing](./ScreenShots/LandingJobPage.png) | Browse jobs with cards and details panel |
| Pagination | ![Viewing](./ScreenShots/ViewingJobs.png) | Navigate through multiple job pages |
| Job Details | ![Selected](./ScreenShots/SelectedJobGoogle.png) | View complete job information |
| Filter by Type | ![Search Types](./ScreenShots/SearchTypes.png) | Filter jobs (Full-time, Internship, etc.) |
| Search Feature | ![Searching](./ScreenShots/SearchingForJob.png) | Find jobs by keywords |
| Job Card | ![Card](./ScreenShots/JobCard.png) | Compact job information display |
| Save Job | ![Saving](./ScreenShots/SavingGameDevJob.png) | Save jobs with visual feedback |
| My Jobs | ![My Jobs](./ScreenShots/MyJobs.png) | Track saved and applied jobs |
| Remove Saved | ![Remove](./ScreenShots/RemovingSavedJob.png) | Remove saved jobs instantly |
| Apply Process | ![Applying](./ScreenShots/ApplyingforGameDevJob.png) | Answer screening questions |
| Application View | ![Details](./ScreenShots/ApplicationDeatils.png) | View submitted application |
| Notification Popup | ![Popup](./ScreenShots/NotificationPopUp.png) | Real-time status updates |
| Notification Detail | ![Detail](./ScreenShots/NotificationCloserLook.png) | Detailed notification view |
| Bell Icon | ![Bell](./ScreenShots/NotificationFromBell.png) | Notification dropdown menu |

---

### 🏢 Employer Flow

| Step | Screenshot | Description |
|------|------------|-------------|
| Employer Signup | ![Signup](./ScreenShots/EmployerSiginUp.png) | Register with company details |
| Empty Dashboard | ![Empty](./ScreenShots/DashboardGoogle.png) | Initial state before posting jobs |
| Create Job (Step 1) | ![Create1](./ScreenShots/CreatingJob.png) | Add job title and description |
| Add Skills | ![Create2](./ScreenShots/CreatingJob4.png) | Enter required job skills |
| Success Message | ![Success](./ScreenShots/CreatingJobSucessfully.png) | Job creation confirmation |
| Job Details View | ![Details](./ScreenShots/CreatedJobDetails.png) | View with edit/delete options |
| Dashboard Populated | ![Populated](./ScreenShots/DashboardGoogleAfteraddingJobs.png) | Statistics after adding jobs |
| View Applicants | ![Applicants](./ScreenShots/ViewingApplicants.png) | List of job applicants |
| Application Details | ![App Details](./ScreenShots/ViewingApplicationDetails.png) | Detailed applicant information |
| Status Update | ![Accepted](./ScreenShots/Statuschangedtoaccepted.png) | Accept/reject with auto-notification |

---

## 📂 Project Structure
job-portal/
│
├── README.md # Project documentation
├── Full_Walkthrough.md # Complete screenshot guide
│
├── Backend/
│ └── JobPortal/ # Spring Boot application
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/ # Java source code
│ │ │ │ ├── config/ # Security & JWT config
│ │ │ │ ├── controllers/
│ │ │ │ ├── models/
│ │ │ │ ├── repositories/
│ │ │ │ └── services/
│ │ │ └── resources/ # Properties files
│ │ └── test/ # Unit tests
│ └── pom.xml # Maven dependencies
│
├── Frontend/
│ └── JobPortalFront/ # React + Vite application
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Page components
│ │ ├── context/ # Context API state
│ │ ├── services/ # API service calls
│ │ └── utils/ # Helper functions
│ └── package.json # NPM dependencies
│
└── ScreenShots/ # All application screenshots
├── HomePage.png
├── RegisteringJobSeeker.png
├── DashboardGoogle.png
└── ... (60+ screenshots)

text

---

## 🚀 Getting Started

### Prerequisites

- **Java 17** or higher
- **Node.js 16+** and npm
- **PostgreSQL** database
- **Git** for version control

### Backend Setup

```bash
# Navigate to backend
cd Backend/JobPortal

# Configure PostgreSQL (update application.properties)
spring.datasource.url=jdbc:postgresql://localhost:5432/jobportal_db
spring.datasource.username=your_username
spring.datasource.password=your_password

# Build and run
./mvnw clean install
./mvnw spring-boot:run
Backend runs on: http://localhost:8080

Frontend Setup
bash
# Navigate to frontend
cd Frontend/JobPortalFront

# Install dependencies
npm install

# Start development server
npm run dev
Frontend runs on: http://localhost:5173

Database Setup
sql
-- Create PostgreSQL database
CREATE DATABASE jobportal_db;
🔌 API Endpoints Overview
Category	Endpoints	Methods
Authentication	/api/auth/register, /api/auth/login	POST
Jobs	/api/jobs	GET, POST, PUT, DELETE
Applications	/api/applications	GET, POST, PUT
Saved Jobs	/api/saved-jobs	GET, POST, DELETE
Notifications	/api/notifications	GET, PUT
User Profile	/api/users/profile	GET, PUT
Full API documentation available in the Backend README
🧪 Testing the Application
Test Backend API with cURL
bash
# Register a job seeker
curl -X POST http://localhost:8080/api/auth/register \
  -H "Content-Type: application/json" \
  -d '{"username":"testuser","password":"pass123","email":"test@example.com","role":"SEEKER"}'

# Login to get JWT token
curl -X POST http://localhost:8080/api/auth/login \
  -H "Content-Type: application/json" \
  -d '{"username":"testuser","password":"pass123"}'

# Get all jobs (using token)
curl -X GET http://localhost:8080/api/jobs \
  -H "Authorization: Bearer YOUR_JWT_TOKEN"
📈 What I Learned
Technical Skills
Building REST APIs with Spring Boot and proper HTTP methods
Implementing JWT authentication and role-based authorization
Managing complex database relationships with JPA/Hibernate
Handling file uploads and secure storage
Creating responsive React applications without UI frameworks
Managing application state with Context API

Soft Skills
Planning end-to-end features before coding
Debugging full-stack issues across frontend and backend
Writing clean, maintainable, and modular code
Testing features thoroughly before deployment

Contact 
Nikita - rathinikki36@gmail.com  - 
