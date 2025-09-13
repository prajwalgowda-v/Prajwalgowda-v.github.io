# Copilot Instructions for AI Coding Agents

## Project Overview
This is a static website for Naptico Green Energy Solars, deployed via GitHub Pages. The main content is in `index.html.html`, styled with Tailwind CSS and Font Awesome, and uses Google Fonts (Poppins). All images are stored in the `images/` directory.

## Architecture & Structure
- **Single-page static site**: All logic and UI are in `index.html.html`.
- **Styling**: Uses Tailwind CSS via CDN. Custom styles are embedded in `<style>` tags.
- **Assets**: All images referenced in the HTML are located in `images/`.
- **No build step**: Directly edit HTML and assets; changes are deployed automatically.

## Developer Workflow
- **Deployment**: Pushing to `main` triggers GitHub Actions (`.github/workflows/static.yml`) to deploy the site to GitHub Pages.
- **Manual deploy**: Can be triggered from the Actions tab in GitHub.
- **No local build/test**: Preview changes by opening `index.html.html` in a browser.

## Project Conventions
- **Custom cursor**: The site uses a custom cursor implemented in CSS and JavaScript. All elements use `font-family: 'Poppins', sans-serif` and `cursor: none`.
- **Image usage**: Reference images using relative paths, e.g. `images/Logo.png`.
- **No frameworks**: No React, Vue, or backend code. All interactivity is in vanilla JS within the HTML file.
- **File naming**: Main file is `index.html.html` (note the double `.html`).

## Key Files & Directories
- `index.html.html`: Main site content, styles, and scripts.
- `images/`: All image assets used on the site.
- `.github/workflows/static.yml`: GitHub Actions workflow for deployment.

## Examples
- To add a new image: Place it in `images/`, then reference it in `index.html.html`.
- To update site styles: Edit the `<style>` block in `index.html.html`.
- To deploy: Commit and push changes to `main`.

## External Integrations
- **Tailwind CSS**: Included via CDN in `<head>`.
- **Font Awesome**: Included via CDN in `<head>`.
- **Google Fonts**: Poppins font included via CDN.

## Tips for AI Agents
- Focus on editing `index.html.html` for all site changes.
- Maintain the custom cursor and font conventions.
- Do not add build tools, package managers, or backend code.
- Ensure all image references match files in `images/`.
- Use GitHub Actions for deployment; no manual build required.

---
If any conventions or workflows are unclear, ask the user for clarification or examples.
