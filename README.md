# My Website — Daniel Malváez

A personal portfolio website built with plain HTML and CSS (no frameworks).

## Pages

| File | Description |
|------|-------------|
| `index.html` | Home page — intro, about, most recent project/post, resume (with embedded PDF), and contact |
| `projects.html` | List of projects with category tags and GitHub links |
| `posts.html` | Blog-style post previews with dates |
| `biography.html` | Extended bio — education, research interests, and personal background |

## Structure

```
my-website/
├── index.html
├── projects.html
├── posts.html
├── biography.html
├── style.css
└── images/
    ├── me.jpg
    └── daniel-malvaez-resume.pdf
```

## Navigation

All pages share a consistent nav bar with:
- Social links (LinkedIn, Instagram, GitHub) always visible
- A hamburger menu (☰) that toggles a slide-down panel linking to every page

## Running Locally

Open `index.html` in a browser. For the embedded PDF to render, serve the site over HTTP:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Credits

Originally based on [this tutorial](https://youtu.be/ZPMtug9qExk?si=9hJ8MC54BW8guB3S).
