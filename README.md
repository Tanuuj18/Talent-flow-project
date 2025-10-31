#  TalentFlow – A Mini Hiring Platform

TalentFlow is a **React + Vite-based mini hiring platform** that allows users to manage **job listings, candidates, and assessments** in one place.  
It is built using a **modern front-end tech stack** — React, Tailwind CSS, MSW, Dexie, and Faker.js — and deployed on **Netlify** for seamless hosting and performance.

---

##  Overview

**TalentFlow** simulates a lightweight hiring portal where:
- HR managers can **add and view job openings**.
- Browse a **list of potential candidates** with skill-based search.
- Manage **assessments** for different job roles.
- Uses **Mock Service Worker (MSW)** to simulate APIs in development.
- Includes **fallback mock data** for Netlify production build.

The UI features a **modern orange–white gradient theme** with responsive and elegant styling.

---

##  Tech Stack

| Category | Technology Used |
|-----------|-----------------|
| **Frontend Framework** | [React 19](https://react.dev/) + [Vite](https://vitejs.dev/) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) |
| **Mock API** | [MSW (Mock Service Worker)](https://mswjs.io/) |
| **Database (Local)** | [Dexie.js (IndexedDB Wrapper)](https://dexie.org/) |
| **Fake Data Generator** | [Faker.js](https://fakerjs.dev/) |
| **Routing** | [React Router DOM](https://reactrouter.com/) |
| **Deployment** | [Netlify](https://www.netlify.com/) |

---

##  Key Features

###  Job Listings
- Displays a list of job openings (Frontend Developer, Backend Engineer, etc.)
- Allows adding new job titles dynamically.
- Uses **mock API calls** and **fallback local data** for offline/production support.

###  Candidate Management
- Displays candidate profiles with names, experience, and skills.
- Provides **search filtering** by name or skill keyword.
- Uses responsive grid layout with Tailwind hover effects.

###  Assessments Module
- Lists multiple test categories with difficulty and duration.
- Includes “Start Test 🚀” button for each assessment.
- Designed with animated gradient backgrounds and shadows.

###  User Interface Highlights
- **Orange–White gradient theme** across all pages.
- **Glass-like cards** with hover scaling and shadows.
- Fully **responsive** on desktop and mobile.
- Clean and consistent typography.

---

##  Folder Structure
talentflow/
├── public/
├── src/
│ ├── api/
│ │ └── msw.js # Mock API handlers
│ ├── db/
│ │ └── index.js # IndexedDB (Dexie) setup
│ ├── pages/
│ │ ├── JobsPage.jsx # Job listings page
│ │ ├── CandidatesPage.jsx # Candidate profiles page
│ │ └── AssessmentsPage.jsx # Assessments module
│ ├── App.jsx # App routes and layout
│ └── main.jsx # Entry point
├── tailwind.config.js
├── postcss.config.js
├── package.json
└── vite.config.js

