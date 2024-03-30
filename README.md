Sure, here's the README with a structured format and the `/api/` removed from frontend endpoint URLs:

---

# Frontend README

## Getting Started

To run the frontend of this project, you will need to have Node.js installed on your system. If you haven't already installed Node.js, you can download and install it from [here](https://nodejs.org/).

Once Node.js is installed, you can proceed with the following steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run the command `npm install` to install all the required dependencies.

## Features

### User Authentication

- Users can register for an account to access the dashboard.
- Users can log in to their accounts securely.

### Dashboard

- Upon successful login, users will be directed to the dashboard.
- From the dashboard, users can navigate to different sections of the application.

### Job Page

- Users can view a list of available job postings.
- Users can create new job postings.
- Users can view details of a specific job posting.
- Users can edit existing job postings.
- Users can delete job postings.

### Candidate Page

- Users can view a list of candidates.
- Users can create new candidate profiles.
- Users can view details of a specific candidate.
- Users can edit existing candidate profiles.
- Users can delete candidate profiles.

## Backend API Endpoints

Below is the list of API endpoints used by the frontend:

### User Authentication

- `/auth/register` - Register a new user.
- `/auth/login` - Login an existing user.
- `/auth/logout` - Logout the current user.

### Job Management

- `/jobs` - GET: Get all jobs, POST: Create a new job.
- `/jobs/:id` - GET: Get a specific job by ID, PUT: Update a job, DELETE: Delete a job.

### Candidate Management

- `/candidates` - GET: Get all candidates, POST: Create a new candidate.
- `/candidates/:id` - GET: Get a specific candidate by ID, PUT: Update a candidate, DELETE: Delete a candidate.

Backend Setup
To run the backend of this project, you will also need to have Node.js installed on your system. Additionally, you need to install the nodemon dependency for development purposes. Follow the steps below to set up the backend:
