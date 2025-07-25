# Communion Hub - Discover Local & Online Events

## Overview
Communion Hub is a full-stack event discovery platform developed to help users find and explore various events in their area or online. Designed with performance and interactivity in mind, it integrates Firebase for real-time features and Redux for managing app state.

## Core Features
- Interactive event listing UI
- User Authentication via Firebase
- Search and filter by category or location
- Real-time Firestore updates
- Smooth animations with GSAP
- Mobile responsive design

## Tech Stack
| Component         | Technology                        |
|------------------|------------------------------------|
| Frontend          | ReactJS, Tailwind CSS              |
| State Management  | Redux                              |
| Backend           | Firebase (Auth + Firestore DB)     |
| Animations        | GSAP                               |
| Hosting           | Firebase Hosting / Vercel (optional)|

## Setup Instructions

### Prerequisites
- Node.js and npm
- Firebase Project (with Auth and Firestore enabled)

### Installation
```bash
git clone https://github.com/yourusername/communion-hub.git
cd communion-hub
npm install
```

1. Configure Firebase credentials in `.env`
2. Start the dev server:
```bash
npm start
```

## Upcoming Enhancements
- Event booking or RSVP
- User profiles
- Admin panel for events
- SEO optimization
