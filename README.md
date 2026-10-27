# Febriana Misdianti | Personal Portfolio

A responsive, single-file portfolio website for a Senior Data Scientist and Data & Analytics Leader with 12+ years of experience in fintech, e-commerce and the public sector.

**Live site:** [misdianti.github.io](https://misdianti.github.io/)

## Sections

- **Home:** introduction, portrait and headline outcomes
- **About Me:** summary and technical expertise
- **What I Do:** fraud and risk ML, data quality and governance, experimentation and analytics
- **Work Experience:** timeline of roles from 2013 to the present
- **My Portfolio:** featured projects and case studies
- **Education & Publications:** degrees and published work
- **Stay In Touch:** email, phone, LinkedIn and GitHub

## Features

- Fully responsive layout for mobile, tablet and desktop
- Light and dark mode toggle that follows the system theme and remembers the choice
- Sticky header with smooth scrolling and a mobile menu
- Keyboard-visible focus states and reduced-motion support
- Content stored in plain JavaScript arrays, so text can be edited without touching the layout

## Tech stack

- HTML5 and vanilla JavaScript, with no build step
- [Tailwind CSS](https://tailwindcss.com/) 3.4.17 via the Play CDN
- Google Fonts: Playfair Display (headings) and Poppins (body)

## Project structure

```
.
├── index.html   # the entire site (markup, styles, content and scripts)
├── .nojekyll    # tells GitHub Pages to serve files as they are, with no Jekyll build
└── README.md
```

## Run locally

No installation is needed. Open `index.html` in a browser. An internet connection is required because Tailwind and the fonts load from a CDN.

To use a local server instead:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Customize

All editable content sits at the top of the `<script>` block, under the comment `EDIT YOUR CONTENT HERE`.

| Constant | What it controls |
| --- | --- |
| `PHOTO` | Hero portrait. Paste a `data:image/jpeg;base64,...` string. Aim for about 800 px wide and under 150 KB. |
| `OUTCOMES` | The "Measured outcomes" card in the hero |
| `SKILLS` | Technical expertise groups |
| `SERVICES` | The three "What I Do" cards |
| `EXPERIENCE` | Timeline entries (role, organization, dates, bullet points) |
| `PROJECTS` | Portfolio cards (name, description, tags, link) |

Contact details, education and publications are written directly in the HTML. Search for the email address or the publication titles to edit them.

## Deploy with GitHub Pages

The repository is named `misdianti.github.io`, so GitHub serves it at the root address `https://misdianti.github.io/`.

1. Push `index.html`, `.nojekyll` and `README.md` to the `main` branch.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, then save.
4. Wait for the **pages build and deployment** run in the **Actions** tab to finish. The site updates within a few minutes.

**Why `.nojekyll`?** By default GitHub Pages runs a Jekyll build, which can publish `README.md` as the home page instead of `index.html`. The empty `.nojekyll` file turns that build off, so `index.html` is served exactly as written.

**Changes not showing?** GitHub Pages and browsers cache pages for several minutes. Hard refresh (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows) or open the site in a private window.

## A note on confidentiality

Most of the work described on this site was done for employers and clients, so the source code is not public. The site describes methods, architecture and outcomes only. Any repository linked from the portfolio section is built on public or synthetic data and is independent of employer work.

## Rights

The code structure may be reused as a template. The personal content, including text, photo and career details, is not licensed for reuse. Add a `LICENSE` file if you want to state this formally.

## Contact

- Email: febriana.misdianti@gmail.com
- LinkedIn: [linkedin.com/in/febrianamisdianti](https://linkedin.com/in/febrianamisdianti)
- GitHub: [github.com/misdianti](https://github.com/misdianti/)
