# 🚀 PeakPlan — Enterprise Team Collaboration Platform

A modern full-stack SaaS platform designed for teams to manage projects, collaborate efficiently, and streamline workflows across organizations. Built with scalability and real-world business requirements in mind using the MERN stack.

---

# ✨ Features

### 🔐 Secure Authentication

* Google OAuth authentication
* Email & password login
* Secure session-based authentication
* Persistent login sessions

### 🏢 Workspace Management

* Create and manage multiple workspaces
* Invite team members via email
* Workspace-level access control

### 📁 Project & Task Management

* Create projects and organize workflows
* Task creation, editing, and tracking
* Priority and status management
* Assign tasks to team members
* Advanced filtering and search support

### 👥 Team Roles & Permissions

* Role-based authorization system
* Owner, Admin, and Member permissions
* Protected workspace resources

### 📊 Productivity Dashboard

* Workspace analytics overview
* Task progress tracking
* Team productivity insights

### ⚡ Performance & Scalability

* Pagination and lazy loading
* Optimized API architecture
* Database transaction support
* Scalable multi-tenant design

---

# 🛠️ Tech Stack

## Frontend

* React.js
* TypeScript
* Tailwind CSS
* Shadcn UI
* Vite

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

## Authentication & Security

* Google OAuth
* Cookie-based sessions
* Protected API routes

---

# 📦 Environment Setup

Create a `.env` file in the root directory and configure the following variables:

```env
PORT=8000
NODE_ENV=development

MONGO_URI=your_mongodb_connection_string

SESSION_SECRET=your_session_secret

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

GOOGLE_CALLBACK_URL=http://localhost:8000/api/auth/google/callback

FRONTEND_ORIGIN=http://localhost:3000
FRONTEND_GOOGLE_CALLBACK_URL=http://localhost:3000/google/callback
```

---

# 🚀 Installation & Running Locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Backend server will run on:

```bash
http://localhost:8000
```

---

# 🌍 Use Cases

* Startup team collaboration
* Internal company project management
* Agile sprint planning
* Remote team coordination
* SaaS productivity platforms

---

