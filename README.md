# Job Founder Microservices Frontend Project App

## Overview
Contains the frontend application for the Job Founder Microservices project, built using modern web development technologies. The project aims to provide a user-friendly interface for managing job-related functionalities in a microservices architecture.

## Features
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Microservices Integration:** Seamlessly integrates with backend microservices.
- **User Authentication:** Secure login and registration system.
- **Job Management:** Features for job posting, editing, and searching.
- **Real-time Updates:** Utilizes WebSockets for real-time data updates.

## Technologies
- **Frontend:** React, JavaScript, HTML, CSS, Context API
- **Build Tool:** Vite
- **Containerization:** Docker
- **Linting:** ESLint
- **CI/CD Pipeline**

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Chanuth-silva10/job-founder-microservices-frontend-project-app.git
   ```

2. Navigate to the project directory:
  ```bash
  cd job-founder-microservices-frontend-project-app
  ```

3. Install dependencies:
  ```bash
  npm install
  ```

4. Start the development server:
  ```bash
  npm run dev
  ```

## Docker
To run the application in a Docker container:
```bash
docker build -t job-founder-frontend .
docker run -p 3000:3000 job-founder-frontend

```
