# Dr. Hoan Ngoc Doan - Academic Personal Website

This repository contains the source code and static assets for the personal academic homepage of **Dr. Hoan Ngoc Doan (TS. Đoàn Ngọc Hoan)**, Lecturer and Principal Investigator at the School of Biomedical Engineering (BME), International University – Vietnam National University Ho Chi Minh City (HCMIU, VNU-HCM).

---

## 🌟 Key Features

- **Modern & Fast**: Zero build steps, zero node_modules dependencies. Built with Tailwind CSS, Lucide Icons, and vanilla JavaScript.
- **Dark/Light Mode**: Smooth system-aware theme toggle with persistent preference in `localStorage`.
- **Live Publications Engine**: Instant client-side search and category filtering across all **71 publications & conference proceedings** (WoS/Scopus Q1/Q2, National journals, conferences, with Google Scholar citation counts).
- **Comprehensive Academic Dossier**:
  - **3 Core Research Pillars**: Hemostatic Dressings, 3D Tissue Engineering Scaffolds & dECM, Functional Nanofibers & Smart Sensors.
  - **Funded Research Grants**: NAFOSTED PI (2024–2027), VNU-HCM Type C PI (2024–2026), Ben Tre Provincial Grant PI (2023–2025), HCMIU PI (2025–2027).
  - **Patents**: IP Vietnam Application No. `1-2025-03421` and Application No. `VN1202409088` (1-2024-09088).
  - **Editorial Roles & Honors**: Young Editorial Board (*Collagen and Leather*, Q1 Springer Nature), VNU-HCM President's Certificate of Merit, MEXT, JASSO.

---

## 🚀 Deployment Instructions

You can host this website completely **FREE** forever with custom domain support on either **GitHub Pages** or **Vercel**.

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub Repository**:
   - Go to [GitHub.com](https://github.com/new) and create a repository named either:
     - `hoan-doan` (will be published at `https://<your-username>.github.io/hoan-doan/`)
     - Or `<your-username>.github.io` (will be published at root `https://<your-username>.github.io/`)
2. **Push Website Files**:
   In your terminal (inside this folder `Academic_Website`):
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit of modern academic website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to your repository on GitHub -> **Settings** -> **Pages**.
   - Under **Build and deployment** > **Source**: choose **Deploy from a branch**.
   - Branch: select `main` / folder: `/(root)` -> click **Save**.
   - Your site will be live in 1–2 minutes!

---

### Option 2: Vercel (Instant 1-Click Drag & Drop)

1. Log in to [Vercel](https://vercel.com).
2. Go to your **Dashboard** -> click **Add New...** -> **Project**.
3. Either:
   - **Import Git Repository**: Connect the GitHub repository created above (Vercel auto-detects `vercel.json` and deploys instantly on every push).
   - **Or Drag & Drop**: Using Vercel CLI:
     ```bash
     npm i -g vercel
     vercel deploy --prod
     ```
4. Done! Your site is live at `https://<project-name>.vercel.app`.

---

## 📁 Directory Structure

```text
Academic_Website/
├── .nojekyll                          # Bypasses Jekyll processing on GitHub Pages
├── vercel.json                        # Cache and routing headers for Vercel
├── index.html                         # Main responsive single-page application
├── README.md                          # Documentation and deployment guide
└── assets/
    ├── avatar.jpg                     # Official portrait photo
    └── publications_data.json         # Structured JSON data of all 71 publications
```

---

## 📬 Contact & Inquiries

- **Email**: [dnhoan@hcmiu.edu.vn](mailto:dnhoan@hcmiu.edu.vn) | [ngochoandoan@gmail.com](mailto:ngochoandoan@gmail.com)
- **Affiliation**: School of Biomedical Engineering, International University, Vietnam National University Ho Chi Minh City.
