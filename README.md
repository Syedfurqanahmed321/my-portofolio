# Syed Furqan Ahmed - Personal DevOps Portfolio Website

A fresh, bright, modern, and animated personal portfolio website designed for **Syed Furqan Ahmed** (Computer Science Student | Linux & DevOps Intern).

Built specifically to showcase hands-on competencies in **Linux System Administration**, **DevOps & Containers (Docker, Kubernetes)**, **Cloud (AWS)**, and **Networking (CCNA)** without exaggerated corporate claims or dark "hacker-style" themes.

---

## 🎨 Visual Design & Palette

- **Primary Light Theme:** Soft white backgrounds (`#F8FAFC`, `#FFFFFF`) with subtle pastel section tints (Lavender `#F5F3FF`, Sky Blue `#F0F7FF`, Mint `#F0FDF4`).
- **Accent Highlights:** Electric Blue (`#2563EB`), Violet (`#7C3AED`), Cyan (`#0891B2`), Mint Green (`#059669`).
- **Typography:** Deep navy headings (`#0F172A`) for high contrast and readability, paired with `Plus Jakarta Sans` and `Fira Code`.
- **Dynamic Elements:** Smooth floating tech cards (Kubernetes, Linux, AWS, Docker), animated typewriter role title, responsive navigation, and interactive technical project diagrams.

---

## 📂 Project Structure

```text
/home/furqan/portfolio/
├── index.html                     # Full responsive single-page portfolio
├── Syed_Furqan_Ahmed_CV.pdf       # Official ATS-optimized 1-page PDF resume
├── README.md                      # Documentation & deployment guide
└── assets/
    ├── portrait_clean.png         # Transparent circular tech portrait
    ├── portrait.png               # Original high-res portrait
    └── avatar.jpg                 # Square thumbnail
```

---

## 🚀 Running the Website Locally

You can open and test the website immediately on your laptop using any of the following methods:

### Method 1: Direct File Opening
In your terminal, run:
```bash
firefox ~/portfolio/index.html
# or with default browser:
xdg-open ~/portfolio/index.html
```

### Method 2: Local Python Web Server (Recommended)
```bash
cd ~/portfolio
python3 -m http.server 8000
```
Then open your browser and navigate to:
[http://localhost:8000](http://localhost:8000)

---

## 🌐 Free Online Deployment Guide

### Option 1: GitHub Pages (Recommended & Free)
1. Initialize a Git repository inside `~/portfolio`:
   ```bash
   cd ~/portfolio
   git init
   git add .
   git commit -m "Initial commit of DevOps portfolio"
   ```
2. Create a new repository on your GitHub account (e.g., `furqan-portfolio` or `<your-username>.github.io`).
3. Link and push your repository:
   ```bash
   git remote add origin https://github.com/<your-username>/furqan-portfolio.git
   git branch -M main
   git push -u origin main
   ```
4. In GitHub repository settings:
   - Navigate to **Settings** > **Pages**.
   - Under **Build and deployment**, select **Source: Deploy from a branch**.
   - Choose `main` branch and `/ (root)` folder, then click **Save**.
   - Your website will be live in 1–2 minutes!

### Option 2: Vercel (Instant & Free)
1. Install Vercel CLI or connect your GitHub repository to [vercel.com](https://vercel.com).
2. Run `vercel` inside `~/portfolio` and follow the prompt. It will deploy in under 30 seconds with automated SSL.

### Option 3: Netlify Drop (Zero Setup)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the `portfolio` folder directly into the browser window.
3. Your site is instantly live with a custom shareable URL.

---

## 📄 CV Download Integration
The portfolio contains direct `Download CV` buttons linked to:
`Syed_Furqan_Ahmed_CV.pdf`

Both the button in the top navigation bar and the footer contact banner download the single-page, ATS-optimized PDF resume.

---

## ℹ️ Information to Keep Updated
- **GitHub Link:** Once you have created public repositories showcasing your Kubernetes manifests or Ansible playbooks, you can add your direct GitHub link into the social buttons.
- **LinkedIn Profile:** Currently linked to `https://linkedin.com/in/syed-furqan-0073b5334`.
- **Contact Details:** Phone `+92 321 6153230` and Email `furqanalishah2256@gmail.com`.
