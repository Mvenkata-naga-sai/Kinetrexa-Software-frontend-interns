# RailGo — Train Booking Capstone Project

A high-level production-style frontend capstone project built with **React.js + Vite**. It demonstrates the internship requirements through a realistic train discovery, booking, payment and ticket-management experience.

## Included features
- Responsive modern UI
- Reusable React components
- Train search with route/date/class controls
- Search results with sorting and seat availability
- Passenger details flow
- Payment UI: UPI, card and net banking (demo/simulated)
- Booking confirmation with generated PNR
- My Bookings page backed by localStorage
- Login/authentication demo flow
- Dark/light theme persisted in localStorage
- Analytics dashboard with reusable metric/chart components
- Clean component-oriented folder structure
- Mobile responsive layouts
- Mock train data / API-ready architecture

## Run locally

Requirements: Node.js 18+

```bash
npm install
npm run dev
```

Then open the URL printed by Vite (normally `http://localhost:5173`).

## Production build

```bash
npm run build
npm run preview
```

## Project structure

```text
src/
  components/   # reusable UI components (ready for extraction)
  context/      # application state layer
  data/         # mock/API-ready data
  pages/        # page-level screens
  main.jsx      # application entry and current component implementation
  styles.css    # responsive design system
```

> This is a frontend capstone/demo. Payment processing is intentionally simulated; no real payment gateway or banking credentials are connected.
