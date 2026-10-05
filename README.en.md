[**فارسی**](README.md) | [English](README.en.md)

# Reza.Ranjbar — my personal website

This is an overhaul of my first hand-coded HTML/CSS website. I kept its five-page structure—Home, About, Skills, Portfolio and Contact—along with the navy-and-blue colours, navigation buttons and profile image. Each page has an English and Persian version. The language link opens the matching page in the other language.


## Open the website

- [English website](https://reza05463.github.io/)
- [وب‌سایت فارسی](https://reza05463.github.io/fa.html)
- [My first website](https://reza05463.github.io/first-website/)

To preview locally, open `index.html` or `fa.html` in a browser. There is no JavaScript, framework, package installation or build step. The published files are HTML, CSS and images.

## What is here

- MATLAB image comparison and Laplacian sharpening, with result images.
- My PHP/MySQL Story Library project.
- An unfinished traffic-light model in CPN Tools, with its limitations stated.
- Thirteen university study notes with links to both languages.
- My interests, project tools and email contact.
- My first Persian website, preserved as a small part of my learning history.

## Files

| Path | Purpose |
|---|---|
| `index.html`, `fa.html` | Home in English and Persian |
| `about.html`, `about.fa.html` | About me |
| `skills.html`, `skills.fa.html` | Skills table and interests |
| `portfolio.html`, `portfolio.fa.html` | Projects, study notes and original PDF links |
| `contact.html`, `contact.fa.html` | Email and GitHub contact |
| `style.css` | All layout, colours, mobile styles and button animations |
| `original-theme.css`, `portfolio.css` | Small compatibility files for older uploads; no need to edit |
| `assets/` | MATLAB result images and favicon |
| `first-website/` | Five early pages, their stylesheet and profile image |
| `.nojekyll` | Serve the files directly through GitHub Pages |



## Publish or update

Use my existing repository, **`reza05463.github.io`**. **Reza.Ranjbar** is the displayed name, while the repository name keeps the existing website address working.

1. Upload this folder's contents to the repository root. Keep `assets/` and `first-website/` as folders.
2. In **Settings → Pages**, select **Deploy from a branch**, **main**, and **/(root)**.
3. Save and check the deployment, then check all five pages in both languages and the first-website archive.


## Editing the code

Open the HTML file for the page you want to change. The matching `.fa.html` file contains its Persian text (`fa.html` is the Persian home page). All current pages use one stylesheet: `style.css`. Its numbered comments help you find colours, navigation, page content, mobile layouts and buttons. Section 11 controls the original lift-and-glow button effect. No generator, JavaScript or build command is required.
