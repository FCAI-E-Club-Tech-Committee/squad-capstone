# Capstone Project Proposal: [Project Name]

## 1. Squad Roster & Mandatory Role Matrix
| Member Name | GitHub Username | Assigned Squad Role | Primary Module Ownership |
| :--- | :--- | :--- | :--- |
| [Ahmed Walid] | `@Ahmed-Walid-Badr` | Product & UI/UX Lead | Wireframes, Semantic HTML, Responsive CSS |
| [Youssef Mohmaed] | `@yoyomosman2015-dotcom` | Frontend State & Logic Lead | JS DOM/Events, `localStorage`, Client State |
| [Mahmoud Waleed] | `@mahmoud-soliman-mas` | Backend & Data Lead | Data Modeling, JSON Schemas, Future API & DB |
| [Ahmed Walid] | `@Ahmed-Walid-Badr` | Git & QA Release Lead | Repo Governance, Branch Protection, PR Reviews |


2. Problem Statement
High school students (ages 15–18) and first-year university students often struggle to choose the right Computer Science career track (such as Web Development, Data Science, AI, or Cybersecurity) due to a lack of structured guidance and practical exploration tools. At the same time, fresh graduates and beginner students face difficulty finding real-world collaborative projects to build hands-on experience and showcase their skills before entering the job market. This web application combines CS PathFinder (an interactive career track explorer and roadmap guide) with a Project Marketplace (a platform connecting learners and beginners with practical project opportunities) in one unified ecosystem.
3. Target Users (Personas)
High School Students (Ages 15–18): Students exploring computer science and programming early who need simplified explanations, career comparisons, and clear beginner roadmaps.
First-Year University Students: Freshmen seeking to connect their academic fundamentals with practical specialization tracks and starter projects without feeling overwhelmed.
Fresh Graduates: Recent graduates looking to apply their technical skills to tangible real-world projects, collaborate with peers, and build a strong portfolio for employers.
4. Core MVP Features (20-Week Roadmap)
Feature 1 — UI & Layout (Weeks 1–5): Build a responsive, semantic HTML/CSS interface across `index.html` (landing page), `dashboard.html` (interactive workspace), and `details.html` (track/project inspection and submission forms).
Feature 2 — Interactive State & Storage (Weeks 6–10): Implement interactive track exploration, skill/interest filtering, and client-side state management using JavaScript DOM events and `localStorage` to save user progress and bookmarked projects.
Feature 3 — CRUD & Backend API (Weeks 11–15): Define structured JSON schemas, build a backend API and database, and enable full Create, Read, Update, and Delete (CRUD) operations for marketplace project listings and applications.
Feature 4 — Authentication & Roles (Weeks 16–20): Add user authentication and role-based access control distinguishing between Explorers/Students, Project Creators, and Platform Admins, followed by comprehensive QA testing.
5. Initial Page & Component Map
`index.html` — Landing Page & Value Proposition (overview of CS PathFinder and Project Marketplace, target audience highlights, and quick-start navigation)
`dashboard.html` — Main Interactive Workspace (career path explorer, personalized recommendations, and filterable marketplace project feed)
`details.html` — Item Inspection / Form Submission View (detailed view of a selected CS track or marketplace project, plus forms to post or apply to projects)