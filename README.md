# Priyanshu Prajapati — Personal Portfolio Website
> **"Turning Ideas into Intelligent Technology."**  
> *Aspiring AI Engineer | B.Tech in CSE (Artificial Intelligence), Major SD Singh University*

A high-performance, futuristic personal portfolio website designed and developed for **Priyanshu Prajapati**. This portfolio combines cybernetic minimalism, real-time interactive canvas 3D neural network visualizations, dark/light theme switching, and accessible, responsive engineering.

---

## ⚡ Highlights & Key Features

- **Futuristic AI Identity**: Deep `#080B09` cybernetic palette with electric `#B6FF4A` accents, glassmorphic HUD interfaces, and glowing synaptic connections.
- **Interactive 3D Neural Network Simulation**: Custom Canvas 2D/3D physics engine rendering interactive neural layers, axons, dynamic action potentials (synaptic pulses), and reactive mouse inertia.
- **Honest & Grounded Skill Badges**: Clean distinction between **Learning**, **Exploring**, and **Practiced** status instead of misleading percentage bars.
- **Cybernetic Terminal Widget**: An embedded interactive terminal (`ai-terminal`) in the bottom right where visitors can interactively query Priyanshu's profile, skills, projects, and education.
- **Dual Architecture Ready**:
  1. **Instant Static Production Bundle**: Zero-dependency `index.html` + modular CSS and JS that runs instantly with Python or any static host (GitHub Pages, Cloudflare Pages, Netlify).
  2. **Next.js 14 App Router Bundle**: Modular TypeScript + React + Tailwind CSS code in `src/` ready for Vercel deployment as soon as Node.js is installed.
- **Dark & Light Mode**: Dynamic theme switcher with automatic OS preference detection and `localStorage` persistence without theme flash.
- **Functional Contact Gateway**: Real-time form validation, loading feedback, instant mailto pre-fill generator, and seamless zero-secret configuration for EmailJS / Formspree.

---

## 📁 Project Directory Structure

```text
priyanshu-portfolio/
├── index.html                   # Production-ready single-page website
├── favicon.svg                  # Custom AI monogram SVG favicon
├── site.webmanifest             # Progressive web app & SEO manifest
├── styles/
│   ├── globals.css              # Cyber theme design tokens, resets, base styles
│   ├── components.css           # Navigation, cards, badges, forms, HUD layouts
│   └── animations.css           # Keyframes, transitions, terminal modal, accessibility
├── scripts/
│   ├── neural-canvas.js         # Interactive 3D neural network simulation
│   ├── theme.js                 # Dark/light mode switcher with persistence
│   ├── contact.js               # Form validation, loading states, email gateway
│   └── app.js                   # Nav tracking, scroll reveals, interactive terminal
├── data/
│   └── portfolio-data.js        # Centralized personal info & verified records
├── src/                         # Next.js 14 + React + TypeScript + Tailwind
│   ├── app/
│   │   ├── layout.tsx           # SEO metadata, font variables
│   │   ├── page.tsx             # Interactive Next.js page components
│   │   └── globals.css          # Tailwind CSS directives
│   ├── data/
│   │   └── portfolioData.ts     # Strongly typed data models
│   └── types/
│       └── index.ts             # TypeScript interfaces
├── package.json                 # Next.js scripts and dependencies
├── tsconfig.json                # TypeScript compiler configuration
├── tailwind.config.js           # Cybernetic design tokens configuration
├── postcss.config.js            # PostCSS configuration
└── README.md                    # Project documentation & deployment guide
```

---

## 🚀 Running the Portfolio Locally

### Option 1: Instant Local Run (Recommended — No Node.js required)
You can run the portfolio right away using Python's built-in web server:

```powershell
# Navigate to the portfolio folder
cd "C:\Users\dell\.gemini\antigravity\scratch\priyanshu-portfolio"

# Start the local HTTP server on port 3000
python -m http.server 3000
```
Open your browser and navigate to:
```
http://localhost:3000
```

### Option 2: Next.js Development Server (Requires Node.js)
When Node.js is installed on your machine:

```bash
# 1. Install dependencies
npm install

# 2. Run Next.js in development mode
npm run dev
```
Visit `http://localhost:3000` to view the Next.js application.

---

## 🌐 Deploying to Production

### Deploying to Vercel (1-Click)
1. Push your repository to GitHub: `https://github.com/priyanshuthelegend2005/portfolio`.
2. Log into [vercel.com](https://vercel.com).
3. Click **Add New Project** and select your `portfolio` repository.
4. Vercel will automatically detect the static files or Next.js build and deploy it with a global CDN URL in seconds.

### Deploying to GitHub Pages
1. On GitHub, create a repository named `priyanshuthelegend2005.github.io` (or `portfolio`).
2. Push the files in this folder to the `main` branch.
3. In repository **Settings** → **Pages**, set the source to `Deploy from a branch` → `main` → `/ (root)`.
4. Your site will be live at: `https://priyanshuthelegend2005.github.io/`.

---

## 📬 Contact Form Configuration (Optional EmailJS Setup)

By default, the contact form validates inputs, presents an immediate confirmation alert, and offers a **"Launch Email Client (Pre-filled)"** button sending directly to `priyanshuintershipjob.5678@gmail.com`.

If you wish to enable silent background dispatch via EmailJS:
1. Sign up for a free account at [EmailJS](https://www.emailjs.com/).
2. Create an Email Service and an Email Template.
3. In `index.html`, add your public keys before `scripts/contact.js`:
```html
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
<script>
  window.PORTFOLIO_CONFIG = {
    EMAILJS_SERVICE_ID: "your_service_id",
    EMAILJS_TEMPLATE_ID: "your_template_id"
  };
  emailjs.init("YOUR_PUBLIC_KEY");
</script>
```
*Note: Never expose private API secret keys in frontend code.*

---

## 🔒 Verified Personal Brand & Academic Information

| Item | Verified Detail |
| :--- | :--- |
| **Full Name** | Priyanshu Prajapati |
| **Professional Role** | Aspiring AI Engineer |
| **Degree** | B.Tech in Computer Science and Engineering (Artificial Intelligence) |
| **University** | Major SD Singh University |
| **Academic Standing** | First Year (Graduation: 2030) |
| **Email** | [priyanshuintershipjob.5678@gmail.com](mailto:priyanshuintershipjob.5678@gmail.com) |
| **LinkedIn** | [linkedin.com/in/priyanshu-prajapati-630997411](https://linkedin.com/in/priyanshu-prajapati-630997411) |
| **GitHub** | [github.com/priyanshuthelegend2005](https://github.com/priyanshuthelegend2005) |
| **Upcoming Event** | VibeX Codes 26 (Registered Participant, 15 Nov 2026) |
