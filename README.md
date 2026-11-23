# Hanchen Shu — Personal Website

Source for my personal site: who I am, what I've worked on, and how to reach me.

**Live site:** https://hanchenshu-maker.github.io

I'm an undergraduate at UCLA studying Economics and Mathematics of Computation, and an LTA scholar from Singapore. My work sits where transport, policy and data meet: policy and analytics internships at Singapore's Land Transport Authority, spatial modeling research, and student leadership on campus. This site brings those threads together in one place.

## What's on the site

- **The route so far** — a timeline from Singapore to Los Angeles
- **Work** — roles at UCLA Library and the Land Transport Authority, and earlier experience
- **Research** — *Space, Time, and Spatial Injustice* and *Driving in the Dark*
- **Campus** — leadership and activities at UCLA
- **About** and **Contact**
- **Résumé** — a printable, single-page view of the same content

## How it's built

The site is deliberately simple: one hand-written HTML file with inline CSS and no frameworks, build step or tracking scripts. It loads fast, works without JavaScript-heavy tooling, and is easy to keep up to date.

```
index.html    the whole site (main page + résumé view)
resume.pdf    one-page PDF of the résumé
404.html      page shown for broken links
robots.txt    search-engine crawl rules
sitemap.xml   page list for search engines
```

It's hosted for free on GitHub Pages, which republishes the site automatically whenever `main` changes.

## Running it locally

No install needed. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Updating

Edit `index.html` and commit to `main`; the live site refreshes within a minute or two. Each role or project is a single `<li class="stop">` block, so adding a new entry means copying an existing block and changing the text.

## Contact

- LinkedIn: https://www.linkedin.com/in/hanchenshu/

## License

© 2026 Hanchen Shu. The content of this site (text, résumé details and any images) is mine and may not be reused without permission. You're welcome to borrow ideas from the code structure.
