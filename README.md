# 🌌 Space Portfolio — Isnain Ahmad Jauhari (Aril)

[![Astro](https://img.shields.io/badge/Astro-v4.x-BC52EE?style=flat-square&logo=astro&logoColor=white)](https://astro.build)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Web3Forms](https://img.shields.io/badge/Web3Forms-API-06B6D4?style=flat-square)](https://web3forms.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

Website portfolio interaktif bertema luar angkasa (*Space Theme*) dengan estetika *dark glassmorphism*, animasi kursor kustom, dan showcase karya terstruktur (Web Development, Visual Design, Video Editing, serta Kredensial Resmi Credly).

---

## ✨ Fitur Utama

- 🚀 **Space Aesthetic & Glassmorphism UI:** Desain minimalis bernuansa antariksa gelap (`#030712`) dengan aksen neon cyan (`#22d3ee`).
- 👨‍🚀 **Custom Dual Cursor:** Pointer mouse kustom dengan efek *companion floating astronaut* berbasis linear interpolation (lerp).
- 🪐 **Seamless Infinite Dual Marquee:** Animasi deretan tools & tech stack looping tanpa jeda patah/reset.
- 🗂️ **Categorized Project Vault (`/projects`):** Galeri proyek interaktif dengan filter tab (Web Dev, Design, Video, Sertifikat) dan modal popup detail.
- 🎖️ **Official Credly Badge Verification:** Integrasi digital badge resmi dari Google Cloud & IBM SkillsBuild.
- 📬 **Real-time Contact Form:** Terhubung langsung ke inbox Gmail tanpa backend server menggunakan Web3Forms AJAX & custom toast notification.
- 📱 **Fully Responsive:** Tata letak dinamis dan teroptimasi untuk tampilan Desktop, Tablet, dan Mobile.

---

## 🛠️ Tech Stack & Tools

| Kategori | Teknologi / Tools |
| :--- | :--- |
| **Framework** | [Astro](https://astro.build) |
| **Styling & Icons** | CSS3 / Scoped Styles, Glassmorphism, [Devicon](https://devicon.dev) |
| **Language** | TypeScript, HTML5 |
| **Integrations** | Web3Forms API |
| **Media & Design** | DaVinci Resolve, Adobe After Effect, Canva |

---

## 📁 Struktur Proyek

```bash
space-portfolio/
├── public/
│   ├── projects/          # Gambar & thumbnail showcase karya
│   ├── favicon.svg        # Favicon tab browser
│   └── cursor-*.png       # Aset grafis custom cursor & astronaut
├── src/
│   ├── components/
│   │   ├── CustomCursor.astro   # Logika interaktif kursor astronot
│   │   ├── Hero.astro           # Banner pembuka
│   │   ├── MainContent.astro    # Section About, Tech Stack, Featured, Life Logs, & Contact
│   │   └── Navbar.astro         # Floating capsule navigation
│   └── pages/
│       ├── index.astro          # Landing page utama
│       └── projects.astro       # Galeri arsip proyek & sertifikat lengkap
├── astro.config.mjs
├── package.json
└── tsconfig.json