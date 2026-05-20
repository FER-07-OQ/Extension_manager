# Extension_manager
# Frontend Mentor - Browser Extensions Manager Dashboard

A beautiful, fully responsive, semantic dashboard built with **React.js** and **Vite** that tracks, filters, and manages active browser extensions. This solution cleanly switches themes between Dark Mode and Light Mode, and uses client-side state storage to persist configurations across browser reloads.

![Design Preview](./design/desktop-design-dark.jpg)

## 🚀 Features

- **State Persistence:** Dynamically saves dashboard edits (deletions and active toggle configurations) right into the browser's `localStorage`.
- **Theme Switcher:** Clean dark/light theme switching using global CSS variable tokens driven by a custom React layout engine.
- **Dynamic Category Filtering:** Functional filter pills ("All", "Active", "Inactive") to cleanly filter visible cards instantly.
- **Fully Responsive Auto-Grid:** Implements fluid CSS Grid layouts adapting beautifully across desktop, tablet, and mobile displays without layout breaking.
- **Accessible Interactions:** Semantic HTML markup elements capturing focus states, hover responses, and natural toggle transformations.

---

## 🛠️ Tech Stack & Methods

- **Framework:** [React.js](https://react.dev/) (Component-driven architecture)
- **Build Tool:** [Vite](https://vite.dev/) (Fast Hot Module Replacement)
- **Styling:** Vanilla CSS Custom Properties (Theme tokens) & CSS Grid
- **State Management:** React Hooks (`useState`, `useEffect`)
- **Storage API:** Web Browser Client LocalStorage API

---

## 📂 Project Structure

```text
browser-extension-manager/
├── public/
├── src/
│   ├── components/
│   │   └── ExtensionCard.jsx  <--- Presentational Component for Cards
│   ├── App.jsx                <--- Logic Core & App Synchronization 
│   ├── index.css              <--- Global Layout & Theme Design System
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
