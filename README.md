# Sachangwan Youths Association Website

A full ready-to-run starter project with:

- Youth registration
- Events posting
- Online voting
- Admin dashboard
- PDF export of members
- Yellow, green, and white theme
- Logo area for City of Lake Nakuru
- Background image area for Sachangwan Center

## Tech Stack

- Frontend: React + Vite + Tailwind CSS
- Backend: Node.js + Express
- Database: SQLite
- PDF export: PDFKit

## Project Structure

```bash
sachangwan-youths-association/
├── client/
├── server/
└── README.md
```

## How to Run

### 1. Start the backend

```bash
cd server
npm install
npm start
```

The backend runs on:

```bash
http://localhost:5000
```

### 2. Start the frontend

Open a new terminal:

```bash
cd client
npm install
npm run dev
```

The frontend runs on:

```bash
http://localhost:5173
```

## Admin Login

```text
Username: admin
Password: admin123
```

## Main Pages

- `/` Home page
- `/register` Member registration
- `/events` Events page
- `/voting` Voting page
- `/admin` Admin dashboard/login

## Important Note About Images

This starter includes placeholder SVG files for:

- `client/public/lake-nakuru-logo.svg`
- `client/public/sachangwan-center.svg`

For the final real website, replace them with:

- The actual City of Lake Nakuru logo
- A real photo of Sachangwan Center

Keep the same filenames if you want the site to use them immediately.

## Current Features

### Member Registration
- Saves full name, phone number, and ID number
- Prevents duplicate ID number registration

### Events
- Admin can post events
- Public can view all events

### Voting
- Only registered members can vote
- One vote per ID number
- Admin can add candidates
- Admin can see vote totals

### Admin Tools
- Login page
- View member list
- Post events
- Add candidates
- Download members list as PDF

## Suggested Next Upgrades

- Real admin authentication with hashed passwords
- SMS notifications
- Image uploads for events
- Closed/open voting sessions
- Results PDF export
- Deployment to Render, Railway, or VPS
