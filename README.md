# Junyu Wu — personal homepage

A small, static, Chinese-first personal site for GitHub Pages.

- `index.html`: About, experience, education and selected work.
- `blog.html`: the complete post index, newest first. Each post links to its published Notion language editions.
- `style.css` and `assets/`: responsive styling and local organization logos.

No build step or external dependencies. Publish this directory at the root of a GitHub Pages site. All internal links are relative, so project sites work as well.

Preview locally with `python3 -m http.server 8000 --directory .`, then open http://localhost:8000. Content follows the supplied public Notion reference; external blog links use the public `political-tapir-e51.notion.site` domain.
