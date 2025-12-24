# Medrenaline 2025

## Overview
Medrenaline is a medical conference/event website for Govt. Kilpauk Medical College. The event is scheduled for September 26-28, 2025.

## Project Architecture
- **Frontend**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS with shadcn/ui components
- **Routing**: React Router DOM
- **Animations**: Framer Motion, tsparticles

## Project Structure
```
src/
├── assets/          # Images, fonts, sponsor logos
├── components/      # Reusable components
│   └── ui/          # shadcn/ui components
├── hooks/           # Custom React hooks
├── lib/             # Utility functions
├── pages/           # Page components
├── App.tsx          # Main app component with routing
├── main.tsx         # Entry point
└── index.css        # Global styles
```

## Pages
- **Home (Index)**: Landing page with hero, countdown timer
- **Workshops**: Workshop information
- **Quiz**: Quiz section
- **Other Events**: Additional events (Case Presentation, Medical Debate, Research Paper)
- **Accommodation**: Accommodation details
- **Previous Edition**: Past event information
- **Contact Us**: Contact information

## Running the Project
```bash
npm run dev     # Development server on port 5000
npm run build   # Production build
```

## Recent Changes
- December 24, 2025: Migrated from Lovable to Replit
  - Updated Vite config to use port 5000
  - Configured allowedHosts for Replit proxy
  - Removed Lovable-specific dependencies (lovable-tagger)
  - Removed netlify.toml

## User Preferences
(None recorded yet)
