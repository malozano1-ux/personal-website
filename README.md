# Personal Website

Personal portfolio and CV built with [Quarto](https://quarto.org/). Hosted at **[manuela-lozano.netlify.app](https://manuela-lozano.netlify.app)**.

## About

I'm a Statistics & Data Science and Economics student at UCLA with a focus on machine learning, econometrics, and applied AI. This site showcases my projects, experience, and background.

## Pages

| Page | Description |
|---|---|
| Home | Introduction and links |
| About | Background, skills, and interests |
| Projects | Portfolio of coursework and personal projects |
| Resume | Education, experience, and skills |
| Contact | How to reach me |

## Tech stack

- **Framework:** [Quarto](https://quarto.org/) (R-based static site generator)
- **Styling:** Custom CSS + Cosmo theme
- **Hosting:** Netlify (auto-deploys from this repo)
- **Languages:** R, HTML, CSS

## Project structure

```
personal-website/
├── index.qmd           # Home page
├── about.qmd           # About page
├── projects.qmd        # Projects listing
├── cv.qmd              # Resume / CV page
├── contact.qmd         # Contact page
├── cv.pdf              # Downloadable resume
├── styles.css          # Custom styles
├── _quarto.yml         # Site configuration
├── _publish.yml        # Netlify publish settings
├── images/             # Site images
├── projects/           # Individual project pages
└── _extensions/        # Quarto extensions (quarto-cv)
```

## Running locally

Requires [R](https://www.r-project.org/) and [Quarto](https://quarto.org/docs/get-started/).

```bash
# Clone the repo
git clone https://github.com/malozano1-ux/personal-website.git
cd personal-website

# Preview locally
quarto preview
```

## Contact

**Manuela Lozano** · [malozano1@g.ucla.edu](mailto:malozano1@g.ucla.edu) · [LinkedIn](https://www.linkedin.com/in/manuela-lozano-395670299/)
