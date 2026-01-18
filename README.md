# Micro Frontend Architecture – Header & Footer Integration

This repository demonstrates a **Micro Frontend (MFE) architecture** using **Webpack Module Federation**.  
The project is split into three independent applications:

- **Header App** (Remote)
- **Footer App** (Remote)
- **Home / Main App** (Host)

Each micro app can be developed, deployed, and scaled independently.

---

## 🧱 Architecture Overview
home (Host App)
├── loads headerApp (Remote)
├── loads footerApp (Remote)
└── shares react & react-dom

headerApp (Remote)
└── exposes Header component

footerApp (Remote)
└── exposes Footer component
