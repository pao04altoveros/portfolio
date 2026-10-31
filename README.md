# Portfolio: John Paolo L. Altoveros

Plain HTML and CSS only. No JavaScript, no build step, no installs: edit and upload.

```
index.html       Home
about.html       About Me
projects.html    Projects (with filter buttons)
project.html     Details of every project (one page, opens the one you click)
skills.html      Skills
contact.html     Contact Me
style.css        All styling (colors are at the top)
images/          Photos and project images
cv.pdf           Your CV
robots.txt  sitemap.xml
```

## How the features work without JavaScript
- **Dark / Light button:** a hidden checkbox plus CSS. The page starts in your device's mode.
  The choice is not remembered after you change page or refresh.
- **Mobile menu:** a hidden checkbox plus CSS.
- **Project filter:** radio buttons plus CSS. Pick a category, year and technology.
- **Project pages:** `project.html#project-01` shows only that project (CSS `:target`).

## Add a project
1. In `projects.html`, copy one `<a class="project-card">` block and change the text.
   Set `data-cat`, `data-year` and `data-tech`.
2. In `project.html`, copy one `<article class="project-detail">` block. Its `id` must match the link.
3. If it has a NEW category, year or technology: add a filter button in `projects.html`
   and a rule in `style.css` under "Project filters".

## Deploy on GitHub Pages
1. New public repository named `portfolio`, upload all files.
2. Settings > Pages > Deploy from a branch > `main` / root > Save.
3. Live at https://pao04altoveros.github.io/portfolio/ (tick Enforce HTTPS).
