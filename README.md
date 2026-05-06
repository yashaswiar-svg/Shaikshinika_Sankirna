# Shaikshinika Sankirna

Shaikshinika Sankirna is an AI-powered campus intelligence network that helps students report incidents quickly and helps university teams triage and coordinate response in real time. It combines structured reporting, geospatial intelligence, and incident lifecycle management in a single workflow. The platform is designed to demonstrate how modern AI and UX patterns can improve safety communication during both routine and critical events.

Tagline: Campus Intelligence Network

## Unique Features

- Voice input reporting: Students can dictate incident descriptions directly in the report form.
- Guardian Mode: Admin-triggered emergency mode prompts campus-wide student safety check-ins.
- Anonymous tokens: Anonymous reporters receive a token for private status lookup without identity exposure.
- AI correlation: Incident classification, urgency scoring, duplicate risk, and correlation tags support response prioritization.

## Tech Stack

- React + Vite
- React Leaflet + Leaflet + leaflet.heat
- Context + useReducer state store
- Anthropic Messages API (`claude-sonnet-4-20250514`)
- Modern CSS (variables, animations, responsive layout)

## Run Locally

`npm install && VITE_ANTHROPIC_API_KEY=your_key npm run dev`
