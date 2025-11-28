# NexaWork -- The Next‑Gen Workspace Manager

NexaWork is a modern, full‑stack project and workspace management
platform built using **PostgreSQL, Express.js, React.js, Node.js**, and
powerful workflow automation tools like **Inngest**.\
It allows organizations to manage projects, tasks, members,
notifications, and analytics seamlessly --- all within a single scalable
platform.

------------------------------------------------------------------------

## 🚀 Features

### 🔹 **Multi‑Organization Workspaces**

-   Create multiple organizations\
-   Switch between workspaces\
-   Manage members independently for each organization

### 🔹 **Project & Task Management**

-   Create projects inside each workspace\
-   Add tasks, set due dates, assign members\
-   Track task progress and status updates

### 🔹 **Smart Email Notifications**

-   Automatic email when a task is assigned\
-   Reminder emails on the due date\
-   Powered by **Inngest background jobs**

### 🔹 **User & Role Management**

-   Invite members to workspaces\
-   Manage roles and permissions\
-   View user activity

### 🔹 **Project Analytics**

-   Track completion rate\
-   Monitor team size\
-   Visualize project progress over time

### 🔹 **Secure Authentication**

-   Powered by **Clerk**\
-   Workspace-level identity management

### 🔹 **Real Database Integration**

-   Built using **Neon PostgreSQL**\
-   Store organizations, users, tasks, and projects\
-   Optimized relational schema for scalability

------------------------------------------------------------------------

## 🛠️ Tech Stack

### **Frontend**

-   React.js\
-   Tailwind CSS\
-   Redux Toolkit\
-   Lucide React Icons

### **Backend**

-   Node.js\
-   Express.js\
-   PostgreSQL (Neon)\
-   Prisma ORM\
-   Clerk Authentication\
-   Inngest Job Scheduler

### **Deployment**

-   Vercel (Frontend + Backend Functions)\
-   Neon PostgreSQL Cloud

------------------------------------------------------------------------

## 📁 Folder Structure

    nexawork/
    │
    ├── backend/
    │   ├── src/
    │   │   ├── routes/
    │   │   ├── controllers/
    │   │   ├── prisma/
    │   │   ├── middleware/
    │   │   └── utils/
    │   ├── package.json
    │   └── server.js
    │
    ├── frontend/
    │   ├── public/
    │   ├── src/
    │   │   ├── components/
    │   │   ├── pages/
    │   │   ├── hooks/
    │   │   ├── store/
    │   │   └── app.jsx
    │   ├── package.json
    │   └── vite.config.js
    │
    └── README.md

------------------------------------------------------------------------

## 🚀 Getting Started

### 1️⃣ Clone the repository

``` bash
git clone https://github.com/yourusername/NexaWork.git
cd NexaWork
```

### 2️⃣ Install dependencies

#### Backend

``` bash
cd backend
npm install
```

#### Frontend

``` bash
cd frontend
npm install
```

------------------------------------------------------------------------

## ▶️ Run the development servers

### Backend

``` bash
npm run dev
```

### Frontend

``` bash
npm run dev
```

Open **http://localhost:5173** to view the app in your browser.

------------------------------------------------------------------------

## 🧩 Environment Variables

### **Backend `.env`**

    DATABASE_URL="your_neon_postgres_url"
    CLERK_SECRET_KEY="your_clerk_key"
    INGEST_API_KEY="your_inngest_key"

### **Frontend `.env`**

    VITE_CLERK_PUBLISHABLE_KEY="your_key"
    VITE_API_URL="backend_url"

------------------------------------------------------------------------



## ⭐ Support

If you like this project, please ⭐ the repository --- it motivates
further development!
