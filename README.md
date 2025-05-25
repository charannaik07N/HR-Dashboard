# 💼 HR Dashboard (Advanced)

An advanced HR Performance Dashboard built with **React.js**, **Tailwind CSS**, and **Radix UI**, designed to help HR managers evaluate employee performance, manage bookmarks, and access rich analytics.

---

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

---

## 🧱 Tech Stack

- **Framework**: Next.js (App Router)
- **UI**: Tailwind CSS
- **State Management**: Context API or Zustand
- **Components**: Radix UI
- **Data Handling**: Client-side fetching (optional SSR/SSG for `/analytics`)
- **Charting** (optional): Chart.js
- **Authentication** (optional): NextAuth.js

---

## 🛠️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/hr-dashboard.git
cd hr-dashboard
npm install
npm install @radix-ui/react-select @radix-ui/react-popover @radix-ui/react-checkbox clsx tailwind-merge class-variance-authority

**##Folder structure**
src/
│
├── assets/               # Static assets
├── components/
│   ├── Ui/               # Reusable UI components (button, card, tooltip, etc.)
│   ├── EmployeeCard.jsx
│   └── SearchAndFilter.jsx
│
├── contexts/
│   ├── HRContext.jsx     # Global state management for employees
│   └── ThemeContext.jsx  # Dark/Light theme management
│
├── hooks/
│   ├── useEmployees.js
│   ├── use-toast.js
│   └── use-mobile.js
│
├── lib/
│   └── utils.js
│
├── pages/
│   ├── Analytics.jsx
│   ├── Bookmarks.jsx
│   ├── Dashboard.jsx
│   ├── EmployeeDetails.jsx
│   └── NotFound.jsx
│
├── types/
│   └── employee.js       # Employee typings


##🛠️ Tech Stack
Frontend Framework: React + Vite

Styling: Tailwind CSS

State Management: Context API

Components: Radix UI + Custom Components

Charts: Chart.js

Routing: React Router

Accessibility: Keyboard navigable components

##screenshorts
## UI of Dashboard
![image](https://github.com/user-attachments/assets/e4e9060a-89f3-421f-bc76-9e1912fd02bb)
## Employee Dashboard
![image](https://github.com/user-attachments/assets/82022e4e-4e0d-4f5d-8733-e3bf2bcccb8c)
##projects of Employee
![image](https://github.com/user-attachments/assets/f2e187c1-ee26-434e-bf31-f0fb7614de04)
##feedback 
![image](https://github.com/user-attachments/assets/b9e53b67-b464-4906-8bf2-043441efa279)
##bookmark
![image](https://github.com/user-attachments/assets/a0cbb782-43b7-42f4-a5be-dc0baaf5c7b1)
##Analytics
![image](https://github.com/user-attachments/assets/679d6740-d04a-4a99-bdbf-c68837244a14)






