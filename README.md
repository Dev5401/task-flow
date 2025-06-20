# TaskFlow - Project Management App

TaskFlow is a responsive project management tool built with React. It allows users to create projects and manage tasks in a Kanban-style board (To Do, In Progress, Done). The app includes login functionality, responsive design, and integrates key frontend concepts like state management, API interaction, testing, and performance optimization.

## 🚀 Features

- 🔐 User Authentication (Login)
- 📁 Project List Sidebar
- 📊 Kanban Board with Task Columns
- 📝 Create/Edit/Delete Projects and Tasks
- 🎨 Responsive Design (Mobile, Tablet, Desktop)
- 📦 State Management (Redux/Context API)
- 🔄 RESTful API Integration (mock or backend-ready)
- 🧪 Unit Testing with Jest and RTL
- ⚡ Performance Optimizations (memoization, lazy loading)

## 🛠️ Tech Stack

- **React.js** (Functional Components + Hooks)
- **Redux Toolkit** (or Context API)
- **Tailwind CSS** for styling
- **TypeScript** (optional)
- **Jest + React Testing Library** for testing
- **Axios** for API calls
- **Node.js + Express + MongoDB** (optional backend)

## 📁 Project Structure

src/
├── components/ # Reusable UI components
├── pages/ # Page-level components
├── redux/ # Redux slices and store (if used)
├── services/ # API functions
├── hooks/ # Custom hooks
├── styles/ # CSS and Tailwind config
├── App.tsx # Main app component
└── index.tsx # App entry point

## 📷 Screens

- **Login Page**: Clean and centered form
- **Dashboard**: Header, sidebar, and task board
- **Task Columns**: To Do, In Progress, Done cards

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/taskflow.git
cd taskflow
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

### 4. Run Tests

```bash
npm run test
```
