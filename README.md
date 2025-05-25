📦 Project Setup
🧱 Installation
To get started, clone the repository and install the necessary dependencies:

bash
Copy
Edit
npm install
Additionally, install the following UI and utility libraries:

bash
Copy
Edit
npm install @radix-ui/react-select @radix-ui/react-popover @radix-ui/react-checkbox clsx tailwind-merge class-variance-authority
🎨 Tailwind CSS Setup
Ensure Tailwind CSS is properly configured in your tailwind.config.js file. This project leverages Tailwind for styling, including support for dark mode and responsive design.

🚀 Features
This HR Performance Dashboard provides a powerful interface for HR managers to manage and evaluate employee data. The key features include:

🔍 Employee Search & Filter
Search employees by name, email, or department (case-insensitive).

Multi-select filtering for departments:

Design

Engineering

HR

Finance

Marketing

Operations

Sales

Performance Rating Filter: Filter employees by rating from 0 to 5 stars.

🌗 Dark Mode / Light Mode Toggle
Seamlessly switch between Dark Mode and Light Mode using Tailwind's dark mode support.

📌 Bookmark System
Bookmark any employee for quick access.

Manage bookmarked employees from the Bookmarks page.

Perform quick actions like Promote or Assign to Project (UI only).

👤 Employee Detail View
Click "View" to navigate to a dynamic employee details page.

View full employee profile, including:

Personal info: Name, Email, Phone, Address

Mock Bio and performance history

Performance rating displayed with color-coded badges

Tabbed interface (Overview, Projects, Feedback) with mock data
