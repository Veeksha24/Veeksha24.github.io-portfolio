# My Portfolio

A personal portfolio website built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme, hosted on GitHub Pages.

## 🚀 Quick Start

### 1. Clone or fork this repo
```bash
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io
```

### 2. Install dependencies
```bash
gem install bundler
bundle install
```

### 3. Run locally
```bash
bundle exec jekyll serve
# Visit http://localhost:4000
```

---

## 📁 File Structure

```
.
├── _config.yml          # Site settings — update name, links, nav here
├── _pages/
│   ├── about.md         # Homepage: bio, tech stack, career timeline
│   ├── projects.md      # Portfolio: projects, micro projects, certificates
│   └── publications.md  # Research papers (remove if not needed)
├── assets/
│   └── img/
│       └── profile_picture.jpg   # Your profile photo
├── projects/
│   └── Images/          # Project thumbnail images
│       ├── project1.jpg
│       ├── project2.jpg
│       └── ...
└── Gemfile
```

---

## ✏️ Customisation Checklist

- [ ] `_config.yml` — update your name, email, GitHub, LinkedIn, etc.
- [ ] `_pages/about.md` — replace placeholder bio, timeline, and tech stack
- [ ] `_pages/projects.md` — add your real projects with GitHub links and images
- [ ] `_pages/publications.md` — add papers, or delete the file and remove from `_config.yml` nav
- [ ] `assets/img/profile_picture.jpg` — add your photo
- [ ] `projects/Images/` — add your project thumbnail images

---

## 🌐 Deploy to GitHub Pages

1. Rename the repo to `<yourusername>.github.io`
2. Go to **Settings → Pages → Source** and select the `gh-pages` branch (al-folio uses GitHub Actions to build automatically)
3. Push your changes — the site will be live at `https://yourusername.github.io`

---

## 📄 Theme

Based on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.
