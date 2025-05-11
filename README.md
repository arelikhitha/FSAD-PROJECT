# Project Overview

This project is organized into three main directories:

* **Admin**: Handles administrative functionalities and management tools.
* **Frontend**: The user-facing part of the application, built with modern web technologies.
* **Backend**: The server-side logic, APIs, and database interactions.

## Directory Structure

```
root/
│
├── admin/           # Admin dashboard and management tools
│
├── frontend/        # User interface and client-side application
│
└── backend/         # Server-side logic, APIs, and database management
```

---

## Setup Instructions

### Prerequisites

Ensure you have the following installed:

* Node.js (v18+)
* Git
* Docker (optional, for containerized deployments)

### Clone the Repository

```bash
git clone <repository_url>
cd <repository_name>
```

### Install Dependencies

1. **Admin**

```bash
cd admin
npm install
```

2. **Frontend**

```bash
cd ../frontend
npm install
```

3. **Backend**

```bash
cd ../backend
npm install
```

### Environment Configuration

* Create `.env` files in each directory (`admin`, `frontend`, `backend`) based on the provided `.env.example` files.
* Ensure the correct API endpoints, database credentials, and secret keys are configured.

### Running the Application

#### Admin Panel

```bash
cd admin
npm start
```

#### Frontend

```bash
cd ../frontend
npm start
```

#### Backend Server

```bash
cd ../backend
npm run dev
```

---

## Deployment

You can deploy each part of the project separately using platforms like Vercel, Netlify, or AWS for the frontend and admin, and services like AWS ECS, DigitalOcean, or Heroku for the backend.

---
