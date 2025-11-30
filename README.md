# Upscore-workout-website
Website design and hosting 
# Warren Zeiders Website — Fleek/IPFS Deployment

This repository contains everything you need to deploy the **Warren Zeiders Official Management Website** using React, Vite, Tailwind CSS, and Lucide Icons, hosted on decentralized Fleek/IPFS infrastructure.

## Features

- Responsive artist management site built with React & Tailwind CSS
- Lightning-fast Vite build setup
- Global CDN & HTTPS via Fleek
- Ready for both .com and ENS (.eth) custom domains
- Auto-deploys on GitHub push
- Cost-effective hosting (free tier available!)

## Structure

```
warren-zeiders-website/
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
├── index.html
├── .gitignore
├── README.md        # ← this file!
└── src/
    ├── App.jsx      # Paste/Write full React component here!
    ├── main.jsx
    └── index.css
```

## Quickstart

1. **Clone the repo**

    ```bash
    git clone https://github.com/<your-username>/warren-zeiders-website.git
    cd warren-zeiders-website
    ```

2. **Install dependencies**

    ```bash
    npm install
    ```

3. **Run locally**

    ```bash
    npm run dev
    ```

4. **Build for production**

    ```bash
    npm run build
    ```

5. **Deploy to Fleek**

    - See [`Warren_Zeiders_Fleek_Deployment_Guide.md`](./Warren_Zeiders_Fleek_Deployment_Guide.md) for full instructions!
    - Connect your GitHub repo to Fleek, specify:
      - **Framework:** Vite
      - **Build command:** `npm run build`
      - **Publish directory:** `dist`
      - **Node version:** 18

## Domain Setup

Supports both:
- **Traditional (.com)**: Use domain management in Fleek Dashboard
- **ENS (.eth)**: Insert IPFS content hash in your ENS domain records

## Troubleshooting

- See the deployment guide for fix steps if build or DNS fails.
- Common fixes:
  - Publish directory must be `dist`
  - All React/Tailwind dependencies installed
  - DNS changes may take 24–48 hours

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide React](https://lucide.dev/)
- [Fleek](https://fleek.co/) / [IPFS](https://ipfs.tech/)

## Credits

- **Manager:** Charly Salvatore
- **Company:** underscore works
- **Label:** Warner Records
- **Site:** Warren Zeiders Official Website
- **Deployment Guide:** See [`Warren_Zeiders_Fleek_Deployment_Guide.md`](./Warren_Zeiders_Fleek_Deployment_Guide.md)

© 2025 Warren Zeiders. All Rights Reserved.

---

_For support, see Fleek Discord, Fleek support email, or open a GitHub issue._
