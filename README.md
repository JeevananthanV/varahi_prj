# Zayed Sustainability Prize — Web Portal

[![Repository](https://img.shields.io/badge/GitHub-JeevananthanV%2Fvarahi__prj-blue?logo=github)](https://github.com/JeevananthanV/varahi_prj)
[![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react&logoColor=white)](https://react.dev)
[![Vite](https://img.shields.io/badge/Bundler-Vite-646CFF?logo=vite&logoColor=white)](https://vitejs.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A pixel-faithful reproduction of the **Zayed Sustainability Prize** article and media platform featuring multilingual English and Tamil publishing, timeline filters, and bespoke typography.

---

## 🔗 Repository Links

| Detail | Link |
|---|---|
| **GitHub Repository** | [https://github.com/JeevananthanV/varahi_prj](https://github.com/JeevananthanV/varahi_prj) |
| **Author** | [Jeevananthan V](https://github.com/JeevananthanV) |
| **Dev Server** | `http://localhost:5173` |

---

## ✨ Features

- 🌐 **Bilingual Toggle (EN / தமிழ்)**: Seamless live language switching across article entries with context persistence.
- 📅 **Year Filter Timeline**: Dynamic filtering pills for editions: 2023 · 2024 · 2025 · 2026 · Upcoming.
- 🎨 **Bespoke Design System**: Custom palette (`#1a3a5c`, `#9a3b34`, `#e85a4f`), Playfair Display editorial headlines, DM Sans body text, and customized golden scrollbars.
- 📱 **Responsive Grid & Layout**: Mobile-first design, sticky navigation bar, and structured dark footer grid.

---

## 📁 Project Structure

```
Web_Blog/
├── index.html
├── vite.config.js
├── package.json
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── index.css
    ├── context/
    │   └── LangContext.jsx      # EN / Tamil translations & language state
    ├── components/
    │   ├── Navbar.jsx           # Sticky nav with lang toggle
    │   ├── YearFilter.jsx       # Year pills (2023–Upcoming)
    │   └── Footer.jsx           # Responsive dark footer grid
    └── pages/
        └── ArticlePage.jsx      # Main article layout & reading view
```

---

## 🚀 Getting Started

### Clone

```bash
git clone https://github.com/JeevananthanV/varahi_prj.git
cd varahi_prj
```

### Installation & Development

```bash
npm install
npm run dev
```

Open `http://localhost:5173` to view the application.

---

## 👨‍💻 Author

**Jeevananthan V** — [@JeevananthanV](https://github.com/JeevananthanV)

## License

MIT
