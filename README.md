# Bay Area EV Charging Network Dashboard

A real-time electric vehicle charging station monitoring dashboard built with React and Tailwind CSS.

## Live Demo

https://hannay-sen.github.io/EV-charging-station-dashboard

## Features

- Real-time battery level simulation across 6 charging stations
- Dynamic status system: stations shift between available, charging, and offline automatically
- Click any station card to start or stop charging
- Live clock updating every second
- Animated battery bars on load
- Smooth card transitions and hover effects
- Fully responsive, works on mobile and desktop

## Tech Stack

- React
- Tailwind CSS
- Vite
- GitHub Pages (deployment)

## Setup & running locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/hannay-sen/EV-charging-station-dashboard.git
   cd EV-charging-station-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the dev server**
   ```bash
   npm run dev
   ```
   Vite will start a local dev server (usually at `http://localhost:5173`) with hot reload.

4. **Build for production**
   ```bash
   npm run build
   ```
   Output goes to the `dist/` folder. Preview the production build locally with:
   ```bash
   npm run preview
   ```

5. **Deploy to GitHub Pages**
   ```bash
   npm run deploy
   ```
   This builds the project and publishes `dist/` to the `gh-pages` branch.
