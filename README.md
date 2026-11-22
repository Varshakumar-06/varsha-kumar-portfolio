# ⚡ B. Varsha Kumar — Interactive 3D Developer Portfolio

<div align="center">

<p align="center">
  <a href="https://portfolio-beta-rust-xm0g3t4cy3.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/🌐%20View%20Live%20Portfolio-00E5FF?style=for-the-badge&logo=vercel&logoColor=black" alt="Live Portfolio Website" height="42" />
  </a>
</p>

### [🌐 View Live Portfolio](https://portfolio-beta-rust-xm0g3t4cy3.vercel.app/)

<p align="center">
  <a href="https://www.linkedin.com/in/varsha-kumar-b64822343/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Varshakumar-06" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:varshakumarballi@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

</div>

An ultra-modern, interactive, high-performance developer portfolio engineered with **React 18**, **TypeScript**, **Tailwind CSS**, and **Three.js / React Three Fiber**. Built to showcase engineering innovations across **Embedded Systems**, **VLSI Design**, **IoT**, and **Software Engineering**.

---

## 🌟 Key Features

* **Interactive 3D Graphics:** Dynamic particle systems and responsive hero frame driven by Three.js and `@react-three/fiber`.
* **Engineering Project Showcase:** Detailed modals, circuit telemetry, highlights, and architecture descriptions for hardware & software projects.
* **Responsive Modern UI:** Clean, dark futuristic aesthetic with smooth framer-motion transitions optimized for mobile, tablet, and desktop viewports.
* **Interactive Resume & Certifications:** Comprehensive education milestones (SRM University AP, 2027), skills hierarchy, and verified certifications (Emertxe Embedded Systems, TCS Cybersecurity, IoT & PIC16F877A).
* **Production-Grade Architecture:** Type-safe modular structure built on Vite 5 with sub-second HMR and optimized gzip bundle footprints.

---

## 🛠️ Technology Stack

| Category | Technologies |
| :--- | :--- |
| **Frontend Framework** | [React 18](https://react.dev/) + [Vite 5](https://vitejs.dev/) |
| **Language** | [TypeScript 5](https://www.typescriptlang.org/) |
| **3D & Graphics** | [Three.js](https://threejs.org/) + [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/) + [@react-three/drei](https://github.com/pmndrs/drei) |
| **Styling & Design** | [Tailwind CSS](https://tailwindcss.com/) + PostCSS + Lucide Icons |
| **Animations** | [Framer Motion](https://www.framer.com/motion/) + Canvas Confetti |
| **Deployment** | [Vercel](https://vercel.com/) |

---

## 📂 Project Architecture

```text
Portfolio/
├── public/                     # Static production assets
│   ├── favicon.svg             # Custom portfolio favicon
│   ├── logo.png                # Branding logo
│   ├── varsha-cutout.png       # Transparent hero portrait
│   └── varsha-kumar.jpg        # Profile portrait
├── src/
│   ├── components/             # Reusable UI & view components
│   │   ├── canvas/             # Three.js 3D Canvas & geometric scenes
│   │   │   ├── BackgroundCanvas.tsx
│   │   │   └── Hero3DFrame.tsx
│   │   ├── Hero.tsx            # Hero greeting & action buttons
│   │   ├── About.tsx           # Academic & engineering biography
│   │   ├── Projects.tsx        # Project catalog with interactive filter cards
│   │   ├── ProjectModal.tsx    # In-depth project view with architecture specs
│   │   ├── Skills.tsx          # Classified technical competencies
│   │   ├── Education.tsx       # Timeline of academic achievements
│   │   ├── Certifications.tsx  # Industry training & certifications
│   │   ├── Contact.tsx         # Direct contact links and inquiry form
│   │   ├── Navbar.tsx          # Responsive navigation bar
│   │   └── Footer.tsx          # Attribution and copyright
│   ├── data/
│   │   └── portfolioData.ts    # Single source of truth for projects & profile data
│   ├── types.ts                # TypeScript interfaces and type declarations
│   ├── App.tsx                 # Main layout orchestrator
│   ├── index.css               # Global styling directives and custom animations
│   └── main.tsx                # React DOM entry point
├── index.html
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts
```

---

## 🚀 Local Development Setup

### Prerequisites
* **Node.js** (v18.x or later recommended)
* **npm** or **pnpm**

### 1. Clone the repository
```bash
git clone https://github.com/Varshakumar-06/varsha-kumar-portfolio.git
cd varsha-kumar-portfolio
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run development server
```bash
npm run dev
```

### 4. Build for production
```bash
npm run build
```

---

## 🚢 Continuous Deployment

The production application is continuously deployed via **Vercel** and synchronized with GitHub commits:
* **Live Deployment:** [https://portfolio-beta-rust-xm0g3t4cy3.vercel.app/](https://portfolio-beta-rust-xm0g3t4cy3.vercel.app/)

---

## 👤 Engineering Contact

**B. Varsha Kumar**  
Electronics and Communication Engineering Undergrad — SRM University AP (Class of 2027)  
* **Live Portfolio:** [https://portfolio-beta-rust-xm0g3t4cy3.vercel.app/](https://portfolio-beta-rust-xm0g3t4cy3.vercel.app/)  
* **LinkedIn:** [linkedin.com/in/varsha-kumar-b64822343](https://www.linkedin.com/in/varsha-kumar-b64822343/)  
* **GitHub:** [@Varshakumar-06](https://github.com/Varshakumar-06)  
* **Email:** [varshakumarballi@gmail.com](mailto:varshakumarballi@gmail.com)
