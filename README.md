# Space Station Power Grid Dashboard

A real-time space station power monitoring dashboard built with React and Tailwind CSS.

## Live Demo

https://hannay-sen.github.io/space-power-grid

## Features

- Real-time power level simulation across 6 station modules
- Dynamic status system — modules shift between normal, warning, and critical automatically
- Featured module view — click any module to expand its details
- Live mission elapsed time clock
- Rotating alert ticker with color-coded severity levels
- Smooth animations and transitions on load

## Tech Stack

- React
- Tailwind CSS
- Vite
- GitHub Pages (deployment)

## Setup & running locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/hannay-sen/space-power-grid.git
   cd space-power-grid
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
