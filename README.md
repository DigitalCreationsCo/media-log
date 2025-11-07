# Andres Bryant’s Media Log

A personal, mindful record of books, films, and music — built to turn media consumption into reflection.

---

## Overview
**Andres Bryant’s Media Log** is a **static site** built with **MkDocs** and **Markdown**, designed to capture and organize personal reflections on media — books, films, podcasts, and more.  
It’s not about consumption, but **conscious engagement**: a lightweight digital journal to think deeply about what’s read, watched, and heard.

The project emphasizes simplicity, accessibility, and longevity — a small, quiet corner of the internet to keep thoughts organized and preserved.

---

## Core Features
- **Markdown-first Content:** Each entry is a simple `.md` file — easy to write, edit, and version control.  
- **Clean, Accessible Design:** Minimalist typography and layout for distraction-free reading.  
- **Mobile-Optimized:** Fully responsive MkDocs theme adapted for mobile and tablet use.  
- **Instant Deployment:** Hosted via **Netlify**, with automatic rebuilds on push.  
- **Lightweight and Fast:** Static generation ensures high performance and no dependencies at runtime.  
- **Version Controlled Journal:** Media notes live alongside commit history, creating a timeline of evolving perspectives.

---

## Tech Stack
- **Static Site Generator:** [MkDocs](https://www.mkdocs.org/)  
- **Markup Language:** Markdown  
- **Hosting:** Netlify  
- **Language:** Python  

---

## Project Goals
- Encourage mindful, reflective media consumption.  
- Maintain an elegant, easily maintainable digital record.  
- Enable quick publishing from plain text.  
- Build a timeless and portable personal knowledge archive.

---

## Setup

### Prerequisites
- Python 3.x  
- MkDocs installed globally:  
  ```bash
  pip install mkdocs
  ```

### Local Development
```bash
git clone <repo-url>
cd media-log
mkdocs serve
```
View the site locally at **http://127.0.0.1:8000/**.

### Deployment
This project is configured for **automatic Netlify deployment**.  
Simply connect your GitHub repository to Netlify — it will:
- Detect MkDocs as the build framework.
- Build the site with `mkdocs build`.
- Deploy the generated `/site` directory automatically.

To build manually:
```bash
mkdocs build
```

---

## Content Structure
```
media-log/
│
├── docs/
│   ├── index.md           # Homepage
│   ├── books/
│   │   ├── <book>.md
│   ├── films/
│   │   ├── <film>.md
│   ├── music/
│   │   ├── <album>.md
│   └── essays/
│       ├── reflections.md
│
├── mkdocs.yml             # Site configuration
└── requirements.txt       # Python dependencies
```

---

## Roadmap
- Add search and tag filtering for faster navigation.  
- Integrate reading statistics and visual summaries.  
- Optional RSS feed for new reflections.  
- Support for embedding highlights and excerpts.

---

## License
MIT License

