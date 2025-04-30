# Job Portal

Welcome to the Job Portal! This project is a job board platform where users can sign up as **recruiters** or **job seekers (students)**. 

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Frontend Setup](#frontend-setup)
  - [Backend Setup](#backend-setup)
- [Roles and Functionalities](#roles-and-functionalities)
  - [Recruiter](#recruiter)
  - [Student](#student)
- [Additional Information](#additional-information)

---

## Features

- **Sign-Up/Sign-In** as a **Recruiter** or **Student**.
- **Job Browsing** with filters for easier navigation.
- **Job Applications** tracking and status updates.
- **User Profiles** for students, with image and resume upload through Cloudinary API.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Cloud Storage**: Cloudinary (for profile image and resume uploads)
  
---

## Getting Started

To get a local copy up and running, follow these steps:

Clone the repository:

 ```bash
 git clone https://github.com/jonofficial/Job_Portal.git
 cd Job_Portal
 code .
 ```

### Frontend Setup

Navigate to the frontend folder and start the development server:

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

Navigate to the backend folder and start the development server:

```bash
cd backend
npm install
nodemon index.js
```

## Roles and Functionalities

### Recruiter
- **Create Companies**: Set up different companies in the portal.
- **Create Job Postings**: Post job opportunities under respective companies.

### Student
- **Apply for Jobs**: Browse through job postings and apply.
- **Profile Section**:
  - **Image Upload**: Upload a profile picture via Cloudinary API.
  - **Resume Upload**: Upload your resume through Cloudinary API.
- **Application Tracking**: Track your job applications with status updates (Accepted/Rejected).

---

## Additional Information

- Ensure **Node.js** and **npm** are installed.
- **Cloudinary** account setup is required for profile image and resume uploads.
- Create a `.env` file in the `backend` folder with the following environment variables:

    ```plaintext
    MONGO_URI= "your_mongo_URI"
    PORT= any_port_number
    SECRET_KEY= "your_secret_key"
    CLOUD_NAME= "your_cloudinary_name"
    API_KEY= "your_cloudinary_api_key"
    API_SECRET= "your_cloudinary_api_secret"
    ```

Replace the placeholders with your actual credentials.
