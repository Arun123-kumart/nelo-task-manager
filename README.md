# nelo-task-manager
This project is a Task Manager Application built as part of the NELO React/Node.js assessment. It allows users to create, update, filter, search, and manage tasks with a clean and responsive UI. The application demonstrates strong React fundamentals, reusable components, state management with hooks, Tailwind CSS styling
🚀 Features
✅ 1. CRUD Operations

Add tasks with Title, Description, Priority, and Due Date

Edit tasks (inline or modal)

Delete tasks with confirmation

Toggle Completed / Pending status

Field validation + form reset after submit

🔍 2. Filters & Search

Filter by All, Completed, Pending, Priority

Case-insensitive Debounced Search (Elastic Search style)

Real-time updated results

👤 3. Login & Session Management

Simple login (email + password)

Session stored using sessionStorage

Auto-redirect to dashboard if authenticated

⏳ 4. Debouncing Logic

Implemented using setTimeout inside a custom hook

Prevents unnecessary re-renders while typing

🔁 5. Elastic Search Workflow

Input ➝ Debounce ➝ Filter local data ➝ Render

Matches partial and case-insensitive queries

📬 6. Task Mail Automation (Mock Cron)

Every 20 minutes, a function checks pending tasks

Logs mock email notifications in console

🎨 7. UI / UX

Fully responsive UI with Tailwind CSS

Reusable components (cards, buttons, inputs, modals)

Clean folder structure + modular code

🛠 Tech Stack

React.js

Tailwind CSS

React Router DOM

Custom Hooks

sessionStorage for session handling

📁 Folder Structure (Simplified)
src/
│── components/
│── hooks/
│── pages/
│── utils/
│── App.jsx
│── main.jsx

▶ How to Run
⿡ Clone the repository
git clone https://github.com/your-username/Nelo-Task-Manager.git

⿢ Install dependencies
npm install

⿣ Start the application
npm run dev

📽 Demo Submission (For NELO Assessment)

✔ Complete all features
✔ Screen-record a 1–2 minute continuous demo
✔ Email the video to nelo.careers@gmail.com
 along with your GitHub repo link

👤 Author

Arun Kumar T 
React.js Developer | Cybersecurity Specialist | Full-Stack Learner
