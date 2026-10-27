# Febriana Misdianti | Personal Portfolio

A responsive, single-file portfolio website for a Senior Data Scientist and Data & Analytics Leader with 12+ years of experience in fintech, e-commerce and the public sector.

**Live site:** `https://misdianti.github.io/` (replace after enabling GitHub Pages)

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
└── README.md
```

The portfolio file was created as `portfolio.html`. Rename it to `index.html` so GitHub Pages serves it as the home page.

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

1. Push `index.html` and `README.md` to the repository.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, then save.
4. After a minute or two, the site is available at `https://misdianti.github.io/<repository-name>/`.

To publish at `https://misdianti.github.io/` with no sub-path, name the repository `misdianti.github.io`.

## A note on confidentiality

Most of the work described on this site was done for employers and clients, so the source code is not public. The site describes methods, architecture and outcomes only. Any repository linked from the portfolio section is built on public or synthetic data and is independent of employer work.

## Rights

The code structure may be reused as a template. The personal content, including text, photo and career details, is not licensed for reuse. Add a `LICENSE` file if you want to state this formally.

## Contact

- Email: febriana.misdianti@gmail.com
- LinkedIn: [linkedin.com/in/febrianamisdianti](https://linkedin.com/in/febrianamisdianti)
- GitHub: [github.com/misdianti](https://github.com/misdianti/)
