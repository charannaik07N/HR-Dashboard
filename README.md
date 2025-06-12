# HR Dashboard

A modern, responsive **HR Dashboard** built with **React (Vite)** and **Tailwind CSS**, designed for real-time HR analytics and management.


- 📊 **Interactive UI** for visualizing key HR metrics
- 📁 **API integration** to fetch dynamic employee and company data
- 🔄 **Real-time updates** with clean data flow using React's state management
- 🖥️ **Responsive design** — fully optimized for desktop, tablet, and mobile
- ⚙️ Built with **Vite** for lightning-fast development and build performance
- 🎨 Tailwind CSS for clean, scalable, and utility-first styling

## 🛠️ Tech Stack

- **Frontend:** React (Vite), Tailwind CSS
- **Deployment:** Vercel
- **Data:** REST API integration

## 🚀 Features

### 🏠 Dashboard Homepage
- Fetches employee data from `https://dummyjson.com/users?limit=20`
- Displays employee cards with:
  - Full Name, Email, Age, Department
  - Performance Rating (0–5 stars)
  - Actions: `View`, `Bookmark`, `Promote`

### 🔍 Search & Filter
- Search employees by **name**, **email**, or **department**
- Multi-select filter options by:
  - **Department**:  
    `Design`, `Engineering`, `HR`, `Finance`, `Marketing`, `Operations`, `Sales`
  - **Performance Rating**: from `0` to `5` stars

### 🌗 Dark/Light Mode
- Toggle between **dark mode** and **light mode** using Tailwind's dark class-based system.

### 📌 Bookmark Manager
- Bookmark employees from the dashboard
- Manage bookmarked profiles in the `/bookmarks` page
- Trigger UI actions: `Promote`, `Assign to Project`, or `Remove Bookmark`

### 👤 Employee Detail Page
- Dynamic route: `/employee/[id]`
- Displays:
  - Name, Email, Phone, Address
  - Mock Bio & Performance History
  - Ratings with badges and stars
- Tabbed UI: `Overview`, `Projects`, `Feedback` (mock content)

## 🧱 Tech Stack

- **Framework**: Next.js (App Router)
- **UI**: Tailwind CSS
- **State Management**: Context API or Zustand
- **Components**: Radix UI
- **Data Handling**: Client-side fetching (optional SSR/SSG for `/analytics`)
- **Charting** (optional): Chart.js

## 🛠️ Installation
   **npm install @radix-ui/react-select @radix-ui/react-popover @radix-ui/react-checkbox clsx tailwind-merge class-variance-authority**
 

## 📸 Live Demo

👉 [Live Site](https://hr-dashboard-git-main-charan-s-projects-647ac572.vercel.app)

## 📂 Folder Structure


src/
├── components/
├── pages/
├── assets/
├── App.jsx
├── main.jsx
