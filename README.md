# Capstone Project Proposal: Worklift Task manager

## 1. Squad Roster & Mandatory Role Matrix
| Member Name | GitHub Username | Assigned Squad Role | Primary Module Ownership |
| :--- | :--- | :--- | :--- |
| Yassin Mohamed | `@yassinmohamed1111` | Product & UI/UX Lead | Wireframes, Semantic HTML, Responsive CSS |
| Ali Abdelhamid | `@Ali-Abdelhamid100` | Frontend State & Logic Lead | JS DOM/Events, `localStorage`, Client State |
| Gasser Ahmed | `@xXSHADOW4Xx` | Backend & Data Lead | Data Modeling, JSON Schemas, Future API & DB |
| Eyad Abdelhakim | `@Eyadhakim` | Git & QA Release Lead | Repo Governance, Branch Protection, PR Reviews |

## 2. Problem Statement
University students juggling heavy academic schedules alongside off-campus responsibilities (part-time jobs, internships, student activities, volunteering, and personal errands) often struggle to prioritize what matters most right now. Heavy all-in-one tools like Notion feel bloated, slow, and overly complex for quick daily execution, leading to missed deadlines, constant context switching, and poor visibility into whether time is actually going toward urgent/important tasks.

This web application solves that pain point by providing a fast, lightweight task manager structured around **Daily, Weekly, and Monthly** horizons, built-in priority ranking, continuous progress tracking, and clear task analytics—without heavy resource overhead or complicated setup.

## 3. Target Users (2–3 Personas)
- **User Type 1: The Overloaded Off-Campus Student:** A university student balancing lectures, assignments, and exams with off-campus work, internships, or extracurriculars. Needs fast priority sorting and clear separation between today's immediate tasks and weekly/monthly commitments.
- **User Type 2: The Structured Planner Student:** A student who wants consistent follow-up across daily, weekly, and monthly goals and uses completion/priority analytics to spot bottlenecks, overload periods, and procrastination habits.
- **User Type 3: The Lightweight Speed-First User:** A student who previously dropped heavy workspaces (like Notion) because of slow loading, clutter, or over-engineering, and wants an instant, distraction-free workspace.

## 4. Core MVP Features (20-Week Roadmap)
1. **Feature 1 (UI & Layout):** Clean, fast, and responsive interface organized into **Daily**, **Weekly**, and **Monthly** views with clear priority badges (e.g., High / Medium / Low) and minimal visual clutter.
2. **Feature 2 (Interactive State & Storage):** Real-time task creation, priority reordering/filtering, status toggling, and horizon switching (Daily / Weekly / Monthly) persisted locally via `localStorage` for instant load times and offline-friendly responsiveness.
3. **Feature 3 (CRUD & Backend API):** Full Create, Read, Update, and Delete operations backed by structured JSON schemas, a REST API, and database persistence, plus a **Task Analytics** module showing completion rates, tasks by horizon (Daily/Weekly/Monthly), priority breakdown, and overdue/carry-over trends.
4. **Feature 4 (Authentication & Roles):** User registration, login/logout, session/token handling, and role-based access (e.g., `Student User` vs. `Admin` for system monitoring/support), isolating each user's tasks and analytics data securely.

## 5. Initial Page & Component Map
- `index.html` — Landing Page & Value Proposition (lightweight speed vs. heavy tools, Daily/Weekly/Monthly workflow overview, and analytics preview)
- `dashboard.html` — Main Interactive Workspace (Daily / Weekly / Monthly task boards or lists, priority filters, quick-add bar, and analytics summary cards/charts)
- `details.html` — Item Inspection / Form Submission View (create or edit a task, set horizon, priority, due date, subtasks/notes, and inspect task history or status)