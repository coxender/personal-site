# Resume Portfolio on GitHub Pages

This repository is a static portfolio site designed for GitHub Pages. It publishes:

- A home page that highlights your profile, skills, and experience
- Three LaTeX resume variants for:
  - Backend Engineer
  - AI/ML Engineer
  - Security-Focused Developer
- An automated GitHub Actions pipeline that compiles the resumes into PDF files and deploys the site

## Project structure

- `site/` - static website files served by GitHub Pages
- `resumes/` - LaTeX resume sources
- `.github/workflows/` - build and deploy automation

## Customize the content

Update these files with your real information:

- `site/index.html`
- `resumes/backend-engineer.tex`
- `resumes/ai-ml-engineer.tex`
- `resumes/security-focused-developer.tex`

## Deployment

1. Push this repository to GitHub.
2. In the repository settings, open `Pages`.
3. Set the source to `GitHub Actions`.
4. Push to `main` again or run the workflow manually.

The workflow compiles the LaTeX resumes and deploys the contents of `site/` to GitHub Pages.
