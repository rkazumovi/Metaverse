Metaversus 🪐

A modern, animated landing page for a fictional metaverse platform — built with Next.js, Tailwind CSS, and Framer Motion, based on a Modern UI/UX Framer Motion Figma design.

🔗 Live Demo: https://metaverse-eta-three.vercel.app/
🎨 Design Source: https://www.figma.com/design/EyzNoOFak1Nb1bBx9ZKI7E/Modern-UI%2FUX-Framer-Motion


Overview

Metaversus is a concept landing page for an imaginary metaverse platform where users can explore different virtual worlds through VR. The project translates a Figma UI/UX design into a fully coded, responsive web app, with smooth scroll-triggered animations powered by Framer Motion throughout every section.

The page walks visitors through the product story: an introduction to the concept, a showcase of explorable virtual worlds, a simple "how it works" breakdown, feature highlights, social/insight content, and a closing call-to-action.

✨ Features


⚡️ Built with Next.js 13 (pages router)
🎬 Rich scroll and interaction animations via Framer Motion
🎨 Styled entirely with Tailwind CSS
📱 Fully responsive across desktop, tablet, and mobile
🧩 Component-driven architecture — each page section is its own reusable component
🖼️ Custom illustrations and world showcase cards


🧭 Sections

SectionDescriptionHeroLanding intro to the Metaversus conceptAboutExplains what the metaverse is and its appealWorldShowcase of explorable virtual worlds (e.g. Hogwarts, Upside Down, Paradise Island)Get StartedSimple 3-step guide to entering the metaverseWhat's NewHighlights recent platform updatesExploreSocial feature for finding and connecting with friendsInsightsBlog-style cards with metaverse news and tipsFeedbackFounder/testimonial quote section

📊 Languages

LanguageUsageJavaScript94.6%CSS5.4%

🛠️ Tech Stack


Next.js — React framework (pages router, static export)
React — UI library
Tailwind CSS — utility-first styling
Framer Motion — animation library
ESLint (Airbnb config) — linting and code consistency


🚀 Getting Started

Prerequisites


Node.js (v16 or later recommended)
npm


Installation


Clone the repository


bash   git clone https://github.com/rkazumovi/Metaverse.git
   cd Metaverse


Install dependencies


bash   npm install


Run the development server


bash   npm run dev


Open your browser and navigate to http://localhost:3000


Build for Production

bashnpm run build

This builds the app and exports it as a static site (via next export), ready to deploy to Vercel, Netlify, or any static host.

Lint

bashnpm run lint

📁 Project Structure

Metaverse/
├── app/                 # App-level setup
├── components/          # Reusable UI components (Navbar, Footer, Cards, etc.)
├── constants/           # Static content and config data
├── pages/               # Next.js pages (routing)
├── public/              # Static assets (images, icons)
├── sections/            # Page sections (Hero, World, About, WhatsNew, etc.)
├── styles/              # Global styles
├── next.config.js
├── tailwind.config.js
├── postcss.config.js
└── package.json

🎨 Design Credit

The visual design for this project is based on a Modern UI/UX Framer Motion Figma template. This repository contains an original, hand-coded implementation of that design using Next.js, Tailwind CSS, and Framer Motion.

📦 Deployment

This project is deployed on Vercel and can be viewed live at:
👉 metaverse-eta-three.vercel.app

🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you'd like to contribute.

📄 License

This project is intended for educational and portfolio purposes. The original design assets are property of their respective creators and subject to their licensing terms.


<p align="center">Made with ❤️ using Next.js + Tailwind CSS + Framer Motion</p>
