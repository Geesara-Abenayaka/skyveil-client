# Skyveil — Music Festival Management & Ticketing Frontend

A modern, responsive web application for exploring music festivals, purchasing passes, and managing event operations. Built with React and Vite for blazing-fast performance.

---

## 📌 Project Overview

**Skyveil** serves as the user-facing and organizer portal for music festivals. The application delivers an immersive, dark-themed user experience tailored for festival attendees to browse artist lineups, secure passes, and track festival schedules, coupled with an administration workspace for event managers.

### Key Features
- 🎟️ **Festival Discovery & Ticketing:** Browse upcoming music festivals, view artist lineups, and book tickets seamlessly.
- ⚡ **Vite-Powered Performance:** Ultra-fast hot module replacement (HMR) and optimized build bundles.
- 📱 **Fully Responsive UI:** Polished, festival-themed interface optimized for mobile and desktop screens.
- 🔐 **Secure API Integration:** Configured to interact with the backend services via dynamic environment variables.
- 🛡️ **Code Quality:** Enforced with modern ESLint flat configurations (`eslint.config.js`).

---

## 🛠️ Tech Stack

- **Framework:** React
- **Build Tool:** Vite
- **Routing:** React Router DOM
- **Styling:** CSS3 / Modern Dark Theme
- **Code Linting:** ESLint

---

## 📁 Repository Structure

```text
├── public/                 # Static assets, festival icons, and logos
├── src/                    # Application source code
│   ├── assets/             # Media and styling assets
│   ├── components/         # Reusable UI components
│   ├── pages/              # View pages (Home, Lineup, Tickets, Admin)
│   ├── App.jsx             # Main routing and layout wrapper
│   └── main.jsx            # React root mount
├── .env.example            # Environment variable template
├── .gitignore              # Git ignored files & node_modules
├── eslint.config.js        # ESLint flat config
├── index.html              # HTML shell
├── package.json            # Dependencies and scripts
└── vite.config.js          # Vite build configuration
