# Capstone Project Proposal: The Handymen
https://github.com/janaeldereny/the-handymen

## 1. Squad Roster & Mandatory Role Matrix
| Member Name | GitHub Username | Assigned Squad Role | Primary Module Ownership |
| :--- | :--- | :--- | :--- |
| [Name 1] | `@janaeldereny` | Product & UI/UX Lead | Wireframes, Semantic HTML, Responsive CSS |
| [Name 2] | `@MalakUsama22` | Frontend State & Logic Lead | JS DOM/Events, `localStorage`, Client State |
| [Name 3] | `@janazawal` | Backend & Data Lead | Data Modeling, JSON Schemas, Future API & DB |
| [Name 4] | `@username4` | Git & QA Release Lead | Repo Governance, Branch Protection, PR Reviews |

## 2. Problem Statement
Finding reliable, skilled technicians and craftspeople (such as electricians, plumbers, carpenters, and painters) in Egypt is often stressful and disorganized. Customers usually rely on word-of-mouth or random social media posts, with no transparent way to compare services, pricing, availability, or trustworthy ratings before booking. Homeowners also struggle to track recurring maintenance, such as water filter replacements or routine appliance servicing, which leads to missed maintenance and unexpected breakdowns.

**Proposed Solution:** The Handymen is a full-stack web platform that connects homeowners with verified local technicians across multiple trades. Technicians create profiles showing their specialty, pricing, available time slots, and customer ratings. Customers can filter and compare technicians, book appointments based on availability, and schedule reminders for recurring maintenance tasks. An admin reviews technician profiles before marking them as verified.

## 3. Target Users (2–3 Personas)
- **User Type 1: Homeowner / Customer.** Needs to find a trusted technician quickly, compare prices and ratings, book a suitable time, and remember recurring maintenance.
- **User Type 2: Technician / Craftsperson.** Needs to reach more customers, showcase services and pricing, manage availability and bookings, and build a reputation through reviews.

## 4. Core MVP Features (20-Week Roadmap)
1. **Feature 1 (UI & Layout):** Responsive landing page, technician listing cards, technician profile pages, and booking forms.
2. **Feature 2 (Interactive State & Storage):** Search and filtering by trade, area, price, and rating, with favorites and filter preferences saved in `localStorage`.
3. **Feature 3 (CRUD & Backend API):** API and database to manage technician profiles, services, time slots, bookings, reviews, and in-app maintenance reminders.
4. **Feature 4 (Authentication & Roles):** Sign-up and login with Customer, Technician, and Admin roles, each with its own permissions. Only customers with completed bookings can leave reviews.

## 5. Initial Page & Component Map
- `index.html`: Landing page and value proposition, with trade categories
- `dashboard.html`: Main workspace for browsing and filtering technicians, and managing bookings and reminders (content depends on user role)
- `details.html`: Technician profile with services, pricing, ratings, available slots, and booking form