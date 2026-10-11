# Moath Aldalati — Portfolio

A sleek, dark-themed developer portfolio built with plain **HTML + CSS + JS** — no frameworks, no dependencies to install.

## 📁 File Structure

```
portfolio/
├── index.html      ← The entire portfolio (single file)
├── resume.pdf      ← DROP YOUR RESUME PDF HERE
└── README.md
```

## 🚀 Quick Setup

### 1. Add your Resume PDF
Drop your resume file into this folder and rename it to `resume.pdf`.  
That's the only file you need to add.

### 2. Open Locally
Just double-click `index.html` — it opens directly in your browser. No server needed.

---

## 🌐 Deploy for Free (Recommended: GitHub Pages)

1. Create a new **public** GitHub repository (e.g., `B2K-MOATH1995.github.io`).
2. Push this `portfolio/` folder contents to the repo root.
3. Go to **Settings → Pages → Source → Deploy from branch: `main` / `/(root)`**.
4. Your site will be live at `https://B2K-MOATH1995.github.io` in ~2 minutes!

### Alternative: Netlify (drag & drop)
1. Go to [netlify.com](https://netlify.com) and sign up free.
2. Drag your entire `portfolio/` folder onto the Netlify dashboard.
3. Done — you get a live URL instantly.

---

## ✏️ Customization

| What to change | Where |
|---|---|
| Profile photo | Replace the 🧑‍💻 emoji in `.hero-avatar-inner` with an `<img>` tag |
| Add new projects | Copy a `.project-card` block in the Projects section |
| Colors | Edit `--accent`, `--accent-2`, `--accent-3` CSS variables at the top |
| Typing phrases | Edit the `phrases` array in the `<script>` tag |

---

## 🎨 Design Highlights

- **Dark Glassmorphism** theme with animated background grid and color orbs
- **Typing animation** in the hero section
- **Scroll-triggered fade-up** animations on every section
- **Floating badges** around avatar
- **Video-only projects** shown with a red "Video Demo" badge + LinkedIn link
- **Fully responsive** — works on mobile, tablet, and desktop
- **Zero dependencies** — no npm, no build step
