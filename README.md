# EduAnalytics Backend

## Overview

EduAnalytics is a comprehensive platform designed to help educators manage and analyze student performance data effectively. The platform provides tools for automating grading, generating detailed performance analytics, and managing classes, all through a user-friendly web interface.

This repository contains the Node.js/Express backend code for the EduAnalytics platform. The backend handles API requests, user authentication, file uploads, AI-based grading, and interactions with MongoDB Atlas for data storage.

## Features

- **User Authentication**: Secure login system using JWT for admins, teachers, and students.
- **Class Management**: Tools for creating and managing classes, assigning students, and tracking performance.
- **AI-Based Grading**: Integration with an AI service to automatically grade student submissions and provide feedback.
- **Data Analytics**: Comprehensive analytics to track class and student performance over time.
- **File Uploads**: Support for uploading student work and answer keys in PDF format.

## Tech Stack

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web framework for Node.js.
- **MongoDB Atlas**: Cloud-hosted MongoDB for database management.
- **Multer**: Middleware for handling file uploads.
- **JWT**: JSON Web Token for authentication.
- **Render.com**: Hosting platform for the backend service.
- **Netlify**: Hosting platform for the frontend service.

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/EduAnalytics-Backend.git
   cd EduAnalytics-Backend
