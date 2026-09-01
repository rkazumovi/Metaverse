# Metaversus 🪐

A modern, animated landing page for a fictional metaverse platform — built with **Next.js**, **Tailwind CSS**, and **Framer Motion**, based on a Modern UI/UX Framer Motion Figma design.

🔗 **Live Demo:** [metaverse-eta-three.vercel.app](https://metaverse-eta-three.vercel.app/)
🎨 **Design Source:** [Modern UI/UX – Framer Motion (Figma)](https://www.figma.com/design/EyzNoOFak1Nb1bBx9ZKI7E/Modern-UI%2FUX-Framer-Motion)

![Next.js](https://img.shields.io/badge/Next.js-13-black?logo=next.js)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-38B2AC?logo=tailwindcss)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-7-black?logo=framer)
![JavaScript](https://img.shields.io/badge/JavaScript-94.6%25-F7DF1E?logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS-5.4%25-1572B6?logo=css3)

---

## Overview

Metaversus is a concept landing page for an imaginary metaverse platform where users can explore different virtual worlds through VR. The project translates a Figma UI/UX design into a fully coded, responsive web app, with smooth scroll-triggered animations powered by Framer Motion throughout every section.

The page walks visitors through the product story: an introduction to the concept, a showcase of explorable virtual worlds, a simple "how it works" breakdown, feature highlights, social/insight content, and a closing call-to-action.

## ✨ Features

- ⚡️ Built with **Next.js 13** (pages router)
- 🎬 Rich scroll and interaction animations via **Framer Motion**, with reusable animation variants (fade, slide, stagger) defined in a shared motion utility
- 🎨 Styled entirely with **Tailwind CSS**
- 📱 Fully responsive across desktop, tablet, and mobile
- 🧩 Component-driven architecture — each page section is its own reusable component
- 🖼️ Custom illustrations and world showcase cards

## 🧭 Sections

| Section | Description |
|---|---|
| **Hero** | Landing intro to the Metaversus concept |
| **About** | Explains what the metaverse is and its appeal |
| **World** | Showcase of explorable virtual worlds (e.g. Hogwarts, Upside Down, Paradise Island) |
| **Get Started** | Simple 3-step guide to entering the metaverse |
| **What's New** | Highlights recent platform updates |
| **Explore** | Social feature for finding and connecting with friends |
| **Insights** | Blog-style cards with metaverse news and tips |
| **Feedback** | Founder/testimonial quote section |

## 📊 Languages

| Language | Usage |
|---|---|
| JavaScript | 94.6% |
| CSS | 5.4% |

## 🛠️ Tech Stack

- **[Next.js](https://nextjs.org/)** — React framework (pages router, static export)
- **[React](https://react.dev/)** — UI library
- **[Tailwind CSS](https://tailwindcss.com/)** — utility-first styling
- **[Framer Motion](https://www.framer.com/motion/)** — animation library
- **ESLint** (Airbnb config) — linting and code consistency

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later recommended)
- npm

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/rkazumovi/Metaverse.git
   cd Metaverse
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Run the development server
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

### Build for Production

```bash
npm run build
```

This builds the app and exports it as a static site (via `next export`), ready to deploy to Vercel, Netlify, or any static host.

### Lint

```bash
npm run lint
```

## 📁 Project Structure

```
Metaverse/
├── app/                 # App-level setup
├── components/          # Reusable UI components (Navbar, Footer, Cards, etc.)
├── constants/           # Static content and config data
├── pages/               # Next.js pages (routing)
├── public/              # Static assets (images, icons)
├── sections/            # Page sections (Hero, World, About, WhatsNew, etc.)
├── styles/              # Global styles
├── utils/               # Shared Framer Motion animation variants
├── next.config.js
├── tailwind.config.js
├── postcss.config.js
└── package.json
```

## 🎨 Design Credit

The visual design for this project is based on a [Modern UI/UX Framer Motion Figma template](https://www.figma.com/design/EyzNoOFak1Nb1bBx9ZKI7E/Modern-UI%2FUX-Framer-Motion). This repository contains an original, hand-coded implementation of that design using Next.js, Tailwind CSS, and Framer Motion.

## 📦 Deployment

This project is deployed on [Vercel](https://vercel.com/) and can be viewed live at:
👉 [metaverse-eta-three.vercel.app](https://metaverse-eta-three.vercel.app/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/rkazumovi/Metaverse/issues) if you'd like to contribute.

## 📄 License

This project is intended for educational and portfolio purposes. The original design assets are property of their respective creators and subject to their licensing terms.

---

<p align="center">Made with ❤️ using Next.js + Tailwind CSS + Framer Motion</p>
