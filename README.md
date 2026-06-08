# ☕ eOzka Cafe

A modern, visually stunning responsive web application designed for a premium cafe experience. Built with a focus on fluid animations, modular components, and absolute user readability across all devices.

[![Live Demo](https://img.shields.io/badge/Demo-Vercel-success?style=for-the-badge&logo=vercel&logoColor=white)](https://e-ozka-cafe-1.vercel.app)
[![React Version](https://img.shields.io/badge/React-19.2-blue?style=for-the-badge&logo=react)](https://react.dev/)
[![Vite Version](https://img.shields.io/badge/Vite-8.0-purple?style=for-the-badge&logo=vite)](https://vite.dev/)

---

## 🌟 Key Features

*   **Fluid Tab Navigation:** Instant single-page navigation rendering Home, Menu, Bookings, Reviews, and Contact sub-components seamlessly.
*   **Persistent Theme System:** Impeccable Light & Dark modes synced instantly via the document root attribute and saved locally across user sessions.
*   **Intuitive Table Booking:** A fully reactive reservation engine supporting custom dates, adaptive guest counts, and interactive data states.
*   **Glassmorphic Design Polish:** Deep visual hierarchy featuring premium backdrops, custom animated desktop cursor tracks, and subtle hover translations.
*   **Actionable Feedback Loops:** Immediate state validation wrapped in crisp auto-dismissing toast notifications and modal receipts.

---

## 🛠️ Tech Stack

### Frontend Core & Build Tools
*   **Library:** React `19.2.6` (Hooks architecture using state, refs, and effects)
*   **Bundler & Environment:** Vite `8.0.12` (Hot Module Replacement optimized)
*   **Icons & Assets:** Lucide React `1.17.0` (Scalable vector layouts)
*   **Styling Architecture:** Pure CSS variables with adaptive mix channels

### Quality Control
*   **Linter:** ESLint `10.3.0` (Hooks dependency array and execution compliance)

---

## 📋 Project Directory Structure

```text
eOzka_Cafe_1/
└── eOzka-cafe/
    ├── src/
    │   ├── components/
    │   │   ├── Navbar.jsx        # Navigation shell with built-in theme toggle
    │   │   └── Footer.jsx        # Global institutional footer links
    │   ├── pages/
    │   │   ├── Home.jsx          # Welcome landing zone with primary CTA actions
    │   │   ├── Menu.jsx          # Categorized culinary layout grids
    │   │   ├── BookVisit.jsx     # Active validation table reservation screen
    │   │   ├── Reviews.jsx       # Client feedback display and push submission portal
    │   │   └── Contact.jsx       # Communication form interface
    │   ├── App.jsx               # Orchestration shell and central reactive states
    │   ├── main.jsx              # Application runtime mounting pipeline
    │   └── index.css             # Main stylesheet containing system color tokens
    ├── index.html                # App node mount frame
    ├── vite.config.js            # Custom bundler flags
    ├── package.json              # Direct dependency and runtime map
    └── eslintrc.js               # Code optimization instructions

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/StillnWater/eOzka_Cafe_1.git
cd eOzka_Cafe_1
```

2. Navigate to the project directory:
```bash
cd eOzka-cafe
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm run dev
```

5. Open your browser and visit:
```
http://localhost:5173
```

---

## 📝 Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint to check code quality |

---

## 🎨 Features in Detail

### Theme System
- Toggle between dark and light themes
- User preference is saved in localStorage
- Applied via `data-theme` attribute on document root

### Custom Cursor
- Coffee-themed SVG cursor
- Smooth animation following mouse movement
- Interactive feedback on click (scale and rotation effects)

### Interactive Forms
- **Book Visit:** Date, time slot, party size, and guest name
- **Reviews:** Submit cafe ratings and comments
- **Contact:** Message form for inquiries

### State Management
- Local state using React hooks (`useState`, `useRef`, `useEffect`)
- Tab-based navigation without external routing library
- Toast notifications with auto-dismiss (3-second timeout)

---

## 🔧 Configuration

### Vite Configuration
The project uses Vite with React plugin for fast development and optimized builds.

### ESLint Rules
The project follows JavaScript and React best practices with ESLint, including:
- React Hook dependencies validation
- React Refresh compatibility

---

## 🌐 Deployment

The project is deployed on Vercel. To deploy your own instance:

1. Push to your GitHub repository
2. Connect to [Vercel](https://vercel.com)
3. Select this repository
4. Deploy automatically

---

## 📧 Contact & Support

For inquiries or suggestions, please reach out through:
- **Contact Form:** Available in the Contact page
- **GitHub Issues:** [Report issues via Saurabh-Mudgal-Dev](https://github.com/Saurabh-Mudgal-Dev/eOzka_Cafe_1/issues) or [via StillnWater](https://github.com/StillnWater/eOzka_Cafe_1/issues)

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🙏 Credits

Original repository: [Saurabh-Mudgal-Dev/eOzka_Cafe_1](https://github.com/Saurabh-Mudgal-Dev/eOzka_Cafe_1)

---

**Enjoy your coffee! ☕**
