WeDoGood – NGO Reporting Dashboard

SDE I/II Take-Home Assignment

🔗 Live Demo

Frontend (Vercel): https://wedogood-assignment.vercel.app/

Backend (Render): https://wedogood-assignment.onrender.com/



---

📌 Project Overview

WeDoGood is a simple NGO reporting dashboard that allows users to:

Submit NGO reports

Perform bulk uploads

View an admin-style dashboard interface


The project focuses on clean structure, clear routing, and deployability rather than feature overload.


---

🛠️ Tech Stack

Frontend

Next.js (Pages Router)

React

Material UI (MUI)

Axios

JavaScript


Backend

Node.js

Express.js

Deployed on Render


Deployment

Frontend: Vercel

Backend: Render



---

⚙️ Setup Instructions (Local)

1️⃣ Clone the repository

git clone <your-github-repo-url>
cd <project-folder>

2️⃣ Install dependencies

npm install

3️⃣ Run the frontend

npm run dev

The app will be available at:

http://localhost:3000


---

🔌 API Usage (Sample)

Base URL:

https://wedogood-assignment.onrender.com/

Example (from frontend using Axios):

axios.get("/api/reports");

> API integration is kept minimal for the scope of this assignment.




---

🖥️ UI Screens / Flow

Home Page: Navigation to Submit, Upload, and Dashboard

Submit Report: User-driven report submission flow

Bulk Upload: Placeholder for batch data handling

Admin Dashboard: Admin-oriented view (basic structure)



---

🧠 Architectural Decisions

Used Next.js Pages Router for simplicity and stability

Separated frontend and backend for clear responsibility

Deployed frontend and backend independently for scalability

Kept UI minimal using Material UI for consistency



---

🤖 Use of AI Tools

AI tools (ChatGPT) were used for:

Debugging deployment issues

Improving code structure

Writing documentation clearly and concisely




---

🚀 Improvements with More Time

If this were a production-grade application, I would:

Add authentication & role-based access

Improve mobile responsiveness

Add proper form validation and error handling

Implement database-backed reporting

Add tests (unit + integration)

Improve dashboard analytics & charts



---

📎 Submission Notes

Application is deployed and accessible via public URLs

Best viewed on desktop (mobile responsiveness can be enhanced)

Focus was on correctness, structure, and deployment readiness



---

✅ Final Submission Link

👉 https://wedogood-assignment.vercel.app/

