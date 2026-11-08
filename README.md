<p align="center">
  <img src="assets/banner.svg" alt="Incial Web - Digital Agency & Brand Platform" width="100%" />
</p>

<p align="center">
  <strong>High-Performance Digital Agency & Technology Platform Engineered with Next.js 16, React 19, GSAP Physics, and Tailwind CSS v4</strong>
</p>

<p align="center">
  <a href="https://github.com/AbinVarghexe/Incial-web/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License" /></a>
  <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/Next.js-16.1-black.svg?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" /></a>
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-19.2-61DAFB.svg?style=for-the-badge&logo=react&logoColor=black" alt="React 19" /></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind-CSS%20v4-38BDF8.svg?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS v4" /></a>
  <a href="https://greensock.com/gsap/"><img src="https://img.shields.io/badge/Motion-GSAP%203.14-88CE02.svg?style=for-the-badge&logo=greensock&logoColor=white" alt="GSAP" /></a>
  <a href="https://www.framer.com/motion/"><img src="https://img.shields.io/badge/Animations-Framer%20Motion%2012-FF0055.svg?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" /></a>
</p>

---

## Overview

**Incial Web** is the flagship web experience for **Incial** ("We build Brand, Business, Beyond."). Built from the ground up utilizing the Next.js 16 App Router and React 19 Server Components, it delivers an ultra-smooth, kinetic user journey powered by GSAP timeline animations, ScrollTrigger scroll physics, and Framer Motion spring solvers.

```
       +---------------------------------------------+
       |           Next.js 16 App Router             |
       |  (Server Components & Dynamic Streaming)    |
       +----------------------+----------------------+
                              |
         +--------------------+--------------------+
         |                                         |
         v                                         v
+------------------------+               +------------------------+
| GSAP & ScrollTrigger   |               | Framer Motion 12       |
| - Magnetic Button Pointers              | - Spring Modals        |
| - Parallax Depth Layers|               | - Route Layout Exits   |
| - Pinned Story Cards   |               | - Interactive Hover FX |
+------------------------+               +------------------------+
                              |
                              v
       +---------------------------------------------+
       |   Tailwind CSS v4 Theme Token Pipeline      |
       +---------------------------------------------+
```

---

## Tech Stack & Architecture

- **Next.js 16 App Router**: Server-side rendering (SSR), Incremental Static Regeneration (ISR), and streaming UI boundaries.
- **React 19**: Modern actions, optimistic transitions, and automatic compiler-assisted memoization.
- **GSAP 3.14 & ScrollTrigger**: Precise timeline management, velocity-based scrubbing, and complex multi-stage path morphing.
- **Framer Motion 12**: Micro-interactions, spring-based gesture damping, and reactive layout animations.
- **Tailwind CSS v4**: Zero-configuration lightning engine with modern CSS theme variables.
- **Geist Variable Typography**: High-legibility modern digital sans-serif typeface with dynamic optical weighting.

---

## Quick Start

### 1. Prerequisites

- Node.js 18.18+ or 20.x
- pnpm / npm / yarn / bun

### 2. Installation & Setup

```bash
# Clone the repository
git clone https://github.com/AbinVarghexe/Incial-web.git
cd Incial-web

# Install dependencies (pnpm recommended)
pnpm install
# or: npm install
```

### 3. Development Server

```bash
pnpm dev
# or: npm run dev
```

Visit `http://localhost:3000` to preview the interactive agency experience.

### 4. Production Build

```bash
pnpm build
pnpm start
```

---

## Project Structure

```
Incial-web/
├── assets/
│   └── banner.svg               # Vector visual banner
├── app/
│   ├── favicon.ico
│   ├── globals.css              # Tailwind v4 import & custom font layers
│   ├── layout.tsx               # Root layout, metadata & font providers
│   └── page.tsx                 # Agency homepage & section components
├── public/                      # Static branding, logos, and vector artwork
├── package.json
├── tsconfig.json
└── next.config.ts
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
