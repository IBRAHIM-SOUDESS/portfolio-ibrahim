# Ibrahim Soudess — Engineering Portfolio

Production web portfolio showcasing security-first software architecture, applied AI systems, and verified certifications (Cisco & IBM SkillsBuild).

**Live Deployment:** [portfolio-ibrahim-kohl.vercel.app](https://portfolio-ibrahim-kohl.vercel.app)

---

## Overview

Built as a fast, bilingual (**EN / FR**) single-page application presenting engineered systems, technical competencies, and verifiable credentials with minimal runtime overhead.

### Key Highlights
- **Bilingual Content Architecture** — Centralized structured dataset (`src/data/portfolioData.js`) powering French and English views without duplicating UI components.
- **Featured Systems Showcase** — Detailed architectural breakdowns for [SecureLink](https://securelink-puce.vercel.app), ITSM Helpdesk, Tekrin, and Livra-Cam.
- **Verified Credentials Integration** — Direct links to official Cisco Networking Academy and IBM SkillsBuild Credly badges.
- **Modern Frontend Toolchain** — React 19, Vite, Tailwind CSS v4, Framer Motion, and Oxlint for rapid linting and production builds.

---

## Architecture

```text
portfolio-ibrahim/
├── public/                 # Static assets
├── src/
│   ├── components/         # Modular UI sections (Hero, Pillars, Projects, Certifications, Contact)
│   ├── data/
│   │   └── portfolioData.js # Bilingual structured content & metadata
│   ├── App.jsx             # Root layout and language state
│   └── main.jsx            # React 19 entry point
├── index.html              # Document shell & SEO metadata
└── vite.config.js          # Vite bundler configuration
```

---

## Local Development

### Prerequisites
- **Node.js** `>= 20.x`
- **npm** `>= 10.x`

### Setup & Commands

```bash
# 1. Install dependencies
npm install

# 2. Start local development server
npm run dev

# 3. Run static analysis (Oxlint)
npm run lint

# 4. Build for production
npm run build

# 5. Preview production bundle locally
npm run preview
```

---

## Security & Licensing

- Vulnerability reports: see [SECURITY.md](./SECURITY.md).
- Licensed under the [MIT License](./LICENSE).
