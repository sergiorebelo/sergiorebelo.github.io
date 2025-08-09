# Sérgio Rebelo — GitHub Pages (Jekyll)

## Quick deploy
1. Create the repository named **sergiorebelo.github.io** (public).
2. Upload this folder structure to the `main` branch.
3. Go to **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main` and `/ (root)`.
4. Wait ~1–2 minutes. Your site will be live at `https://sergiorebelo.github.io`.

## Edit content
- Main content EN/PT: `linkedin-profile-en.md` and `linkedin-profile-pt.md`.
- Sidebar Markdown: `_includes/sidebar/*.md`  
  - `contact.md`, `skills.md`, `certifications.md`, `courses.md`, `languages.md`
- Layout & styles: `_layouts/default.html`, `_includes/sidebar.html`, `assets/css/style.css`.

## Preview locally (optional)
```bash
gem install bundler jekyll
bundle init        # if no Gemfile
bundle add jekyll  # add jekyll
bundle exec jekyll serve
# open http://localhost:4000
```