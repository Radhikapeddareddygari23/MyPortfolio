# Technical Project Documentation: Professional Portfolio Web Application

**Candidate Name:** Radhika Peddareddy gari  
**Target Profiles:** AI/ML Developer | Full Stack Web Developer | Software Engineer  
**Academic Qualification:** B.Tech in Computer Science and Engineering, Malla Reddy College of Engineering and Technology (MRCET) — **8.6 CGPA**  
**Current Experience:** AI Intern at Innovapath IT Solutions PVT LTD (June 2026 – Present)  
**Project Repository:** [MyPortfolio](https://github.com/Radhikapeddareddygari23/MyPortfolio)  
**Project Version:** 2.0.0  
**Date of Completion:** September 20, 2026  

---

## 1. Executive Summary & Objective

This document outlines the architecture, technology stack, social integrations, styling guidelines, and implementation roadmap for the official developer portfolio of **Radhika Peddareddy gari**.

The objective of this project is to build a modern, high-performance, responsive portfolio that:
1. **Presents a Professional Aesthetic:** Clean layout, high visual contrast, harmonious color balance, and polished typography.
2. **Integrates All Verified Social & Contact Channels:** Seamlessly connects recruiters to LinkedIn, GitHub, Email, Telephone, and a cloud-hosted Resume.
3. **Applies Modern Technologies:** Semantic HTML5, advanced modular CSS3 (Flexbox, CSS Grid, media queries, CSS custom properties), and interactive JavaScript.
4. **Highlights Real-World Engineering:** Features academic credentials, internship work in Generative AI/LLMs/FastAPI, and capstone software engineering projects.
5. **Satisfies a 2-Day Delivery Timeline:** Follows a structured milestone roadmap from wireframing to production deployment.

---

## 2. Candidate Profile & Domain Expertise

### 2.1 Core Summary
- **Education:** B.Tech in Computer Science and Engineering from **Malla Reddy College of Engineering and Technology (MRCET)** with a cumulative **8.6 CGPA**.
- **Specialization:** Aspiring AI/ML and Full Stack Developer with an interest in **Generative AI, Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), Agentic AI, and Data Analytics**.
- **Practical Experience:** Hands-on development with Python, FastAPI, Next.js, REST APIs, MySQL, Git, and Integration Testing.

### 2.2 Work Experience
- **Role:** AI Intern  
- **Organization:** Innovapath IT Solutions PVT LTD  
- **Tenure:** June 2026 – Present  
- **Key Responsibilities:**
  - Developing and integrating AI-powered application modules using Python, FastAPI, and MySQL.
  - Exploring and implementing Generative AI workflows, LLM prompts, and RAG pipelines.
  - Participating in frontend-backend API integration, endpoint validation, and integration testing.
  - Collaborating in an agile environment with cross-functional teams to resolve bugs and verify system reliability.

---

## 3. Technology Stack & Architectural Overview

The portfolio is architected as a lightweight, lightning-fast, and accessible web application designed to run smoothly on any web server or static hosting platform.

```
MyPortfolio/
│
├── index.html              # Core Semantic HTML5 structure and content
├── style.css               # Modular CSS3 styling, design tokens, and media queries
├── DOCUMENTATION.md        # Comprehensive technical report and project documentation
└── assets/                 # (Optional) Local media, icons, and assets
```

### 3.1 Architecture Table

| Layer | Technology | Key Implementation Details |
| :--- | :--- | :--- |
| **Structure** | HTML5 (Semantic) | Uses semantic tags (`<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`) to improve accessibility (a11y) and SEO indexability. |
| **Styling** | Vanilla CSS3 | Custom CSS layout using **Flexbox** for alignment and **CSS Grid** for responsive skill/project matrices. Zero bloated third-party frameworks. |
| **Asset Delivery** | Cloudinary CDN | High-speed global asset delivery for profile imagery (`WhatsApp_Image_2026-05-15...`) with responsive image constraints. |
| **Interactivity** | Vanilla ES6+ JavaScript | Smooth anchor link scrolling, active link highlighting, form validation, and 1-click clipboard copy utilities. |
| **Server Support** | Python / Node / Static | Server-agnostic; runs locally via `python -m http.server 3000` or `npx serve .`, and deploys effortlessly to GitHub Pages, Vercel, or Netlify. |

---

## 4. Design System & Visual Aesthetics

### 4.1 Professional Color Palette (Classic Executive Tech)
To maintain high contrast and eliminate illegibility:

```css
/* Color System Tokens */
:root {
  --bg-primary: #f8fafc;       /* Crisp Off-White Base */
  --bg-hero: #edf2f7;          /* Soft Glacier Slate for Hero Banner */
  --bg-card: #ffffff;          /* Pure White for Cards */
  --navbar-bg: #0f172a;        /* Deep Oxford Navy */
  --text-primary: #0f172a;     /* High-contrast Charcoal */
  --text-secondary: #475569;   /* Muted Slate for Subtitles */
  --accent-blue: #2563eb;      /* Professional Royal Blue for Buttons & Links */
  --border-subtle: #e2e8f0;    /* Soft 1px Card Separation */
  --shadow-card: 0 4px 12px rgba(0, 0, 0, 0.05);
}
```

### 4.2 Typography & Sizing
- **Headings:** Modern Clean Sans-Serif (`'Segoe UI'`, system sans-serif) with bold weights (`700`, `800`) for clear hierarchy.
- **Body:** Standard line-height of `1.6` for effortless readability across long descriptions.
- **Profile Image:** Sized at `18vw` – `20vw` with `border-radius: 50%` and `object-fit: cover` to ensure a distortion-free circular frame.

---

## 5. Social Media & Recruiter Integrations

All professional contact channels are directly wired into the application:

1. **LinkedIn Professional Profile:**
   - **Display Text:** `Radhika_linkedin`
   - **Direct URL:** [https://www.linkedin.com/in/radhika-peddareddy-gari-990a56284](https://www.linkedin.com/in/radhika-peddareddy-gari-990a56284)
   - Opens in a new tab with `target="_blank"` and `rel="noopener noreferrer"` for security.

2. **GitHub Code Repositories:**
   - **Display Text:** `Radhika-github`
   - **Direct URL:** [https://github.com/Radhikapeddareddygari23](https://github.com/Radhikapeddareddygari23)
   - Showcases version control proficiency, open-source repositories, and code samples.

3. **Cloud-Hosted Resume:**
   - **Display:** Prominent header CTA button
   - **Direct URL:** [Google Drive Resume](https://drive.google.com/file/d/1BdWQjLUr0EaApTdA6PBn5OJpu13rhGKb/view?usp=drivesdk)
   - Enables recruiters to view or download Radhika's latest resume in one click.

4. **Direct Communication Channels:**
   - **Email:** `radhikapeddareddygari23@gmail.com` (wired with native `mailto:` protocol).
   - **Phone:** `+91 6300281649` (wired with native `tel:` protocol for mobile auto-dialing).
   - **Physical Location:** Sunshine colony, Suraram, Medchal-Malkajgiri, Hyderabad – 500055, Telangana, India.

---

## 6. Detailed Project Technical Summaries

### 6.1 Project 1: Multimedia Steganography Platform
- **Domain:** Cybersecurity, Cryptography & Computer Vision
- **Technologies Used:** Python, OpenCV, NumPy, Cryptography, Flask, Image Processing, Audio & Video Processing, LSB Steganography Algorithms.
- **Technical Breakdown:**
  - **Multimedia Carrier Support:** Engineered an end-to-end security application supporting hidden confidential communication within image (PNG/BMP), audio (WAV), video (MP4), and text files.
  - **Least Significant Bit (LSB) Algorithm:** Implemented bitwise mathematical manipulation to replace low-order bits of carrier files with encrypted data bits, minimizing perceptible noise or artifacting.
  - **Cryptographic Security:** Integrated cryptographic cipher algorithms to encrypt the payload before embedding, guaranteeing confidentiality even if the file is extracted.
  - **Web Dashboard:** Designed a user-friendly Flask interface for drag-and-drop file encoding, decoding, and integrity verification.

### 6.2 Project 2: Fake Review Detection System
- **Domain:** Machine Learning & Natural Language Processing (NLP)
- **Technologies Used:** Python, Machine Learning, Natural Language Processing (NLP), Scikit-learn, Pandas, NumPy, Flask/Streamlit, Matplotlib, Seaborn, MySQL.
- **Technical Breakdown:**
  - **Text Preprocessing Pipeline:** Implemented comprehensive NLP tokenization, lemmatization, stop-word filtering, and TF-IDF (Term Frequency-Inverse Document Frequency) feature vectorization.
  - **Model Training & Classification:** Trained classification models (Random Forest, Naive Bayes, Support Vector Machines) on consumer review corpora to distinguish authentic customer feedback from fraudulent/paid spam.
  - **Sentiment & Feature Analysis:** Analyzed text polarity against star rating metrics to identify sentiment discrepancies.
  - **Interactive Analytics:** Developed an interactive dashboard providing real-time authenticity classification and visual probability metrics.

---

## 7. 2-Day Milestone Implementation Roadmap

This project was scheduled and delivered within a focused 2-day sprint:

```
[Day 1: Foundation & Structure] ───► [Day 2: Refinement, Testing & Documentation]
  ├─ Requirement Gathering            ├─ Experience Section & Internship Details
  ├─ Semantic HTML Structure          ├─ High-Contrast Color System
  ├─ Social Media Wiring              ├─ Responsive Testing & Cross-Browser Validation
  └─ Initial CSS Styling              └─ Comprehensive Documentation (DOCUMENTATION.md)
```

### Day 1: Architecture, Content Strategy & Core Layout
- **Phase 1.1:** Gathered technical requirements, resume details, and verified URLs (LinkedIn, GitHub, Resume, Cloudinary photo).
- **Phase 1.2:** Drafted the semantic HTML5 skeleton featuring Navbar, Hero, Skills categories, Projects list, and Contact section.
- **Phase 1.3:** Established base CSS styling with Flexbox layout, circular profile photo styling (`border-radius: 50%`), and navigation buttons.
- **Phase 1.4:** Verified public delivery of the Cloudinary image asset.

### Day 2: Advanced Integrations, Visual Refinement & Full Documentation
- **Phase 2.1:** Added the **Experience** section documenting Radhika's ongoing **AI Internship at Innovapath IT Solutions PVT LTD**.
- **Phase 2.2:** Solved color contrast challenges by adopting the **Classic Executive Tech** color scheme (`#f8fafc` background with `#0f172a` text).
- **Phase 2.3:** Connected in-page navigation anchors (`#home`, `#skills`, `#projects`, `#experience`, `#contact`) for smooth scrolling.
- **Phase 2.4:** Conducted cross-device testing across Desktop, Tablet, and Mobile viewports.
- **Phase 2.5:** Authored this exhaustive technical documentation (`DOCUMENTATION.md`) ready for submission.

---

## 8. Deployment & Running Guide

### 8.1 Running Locally
The application requires no build steps, bundlers, or package installations:

1. **Clone or open the project folder:**
   ```bash
   cd "MyPortfolio"
   ```
2. **Launch via Python:**
   ```bash
   python -m http.server 3000
   ```
3. **Launch via Node.js (Alternative):**
   ```bash
   npx serve .
   ```
4. Open your web browser and navigate to:
   ```
   http://localhost:3000
   ```

### 8.2 Production Deployment Options

#### Option A: GitHub Pages (Recommended — 100% Free)
1. Commit all files and push to GitHub:
   ```bash
   git add .
   git commit -m "Complete professional portfolio with documentation"
   git push origin main
   ```
2. In your repository on GitHub, navigate to **Settings** > **Pages**.
3. Under **Branch**, select `main` and root folder `/`, then click **Save**.
4. GitHub Pages will publish the portfolio live at:  
   `https://Radhikapeddareddygari23.github.io/MyPortfolio/`

#### Option B: Vercel (Instant Global CDN)
1. Go to [Vercel.com](https://vercel.com/) and click **"Add New Project"**.
2. Import the `MyPortfolio` GitHub repository.
3. Keep default settings and click **Deploy**. Vercel will provide an instant HTTPS domain with automated deployments on future git pushes.

---

## 9. Conclusion & Submission Checklist

- [x] **Professional Visual Design:** High-contrast palette, circular profile frame, and clean typography.
- [x] **Full Social Media Integrations:** LinkedIn, GitHub, Resume, Email, Phone, and Address.
- [x] **Advanced Technologies:** Semantic HTML5, CSS3 Grid/Flexbox, responsive media queries, and Python/AI highlights.
- [x] **Detailed Documentation:** Exhaustive `DOCUMENTATION.md` covering architecture, projects, and roadmap.
- [x] **2-Day Completion:** Delivered on schedule with a clear timeline breakdown.
