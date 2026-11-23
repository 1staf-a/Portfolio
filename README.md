# Istafa Qureshi Portfolio

This repository contains a complete static personal portfolio website for Istafa Qureshi. It is designed as a professional academic and technical portfolio for a Mechanical Engineering PhD student working across computational mechanics, CFD, nonlinear dynamics, fluid-structure interaction, numerical methods, controls, and scientific software development.

The site uses only HTML, CSS, and minimal JavaScript. It has no build step, no package manager, no backend, and no external dependencies, so it can be hosted directly on GitHub Pages.

## Files

- `index.html` - homepage content, sections, and navigation.
- `favicon.png` - IQ browser-tab icon shared by every page.
- `styles.css` - dark monochrome visual system, responsive layout, cards, timeline, buttons, and accessibility states.
- `script.js` - mobile navigation, active navigation highlighting, and current-year footer update.
- `projects/` - static project detail pages.
- `README.md` - editing and deployment notes.

## Editing Content

Most content changes happen in `index.html`.

### Hero Section

Edit the hero name, title, positioning statement, and external links near the top of `index.html`.

Update:

- The hero statement when the research direction becomes more specific.
- The hero fact blocks as research interests and tools evolve.

### About Section

Update the overview paragraphs in the `about` section as the PhD research direction, lab affiliation, advisor information, and dissertation topic become ready to publish.

### Research Collaborations

Each research interest is a compact card in the `research` section. To add a new topic, copy one existing `<article class="topic-card">` block and edit the title and description.

### Projects

Each project is an `<article class="project-card">` block in the `projects` section of `index.html`. Each card links to a matching HTML page inside the `projects/` directory.

To update a project card:

1. Edit the project title.
2. Replace the summary with a specific description.
3. Update the tags in the `<ul class="tag-list">`.
4. Keep the local project page link, or replace it with a repository, report, demo, or paper link if that becomes the preferred destination.

To update a project detail page:

1. Open the matching file in `projects/`.
2. Edit the overview paragraph.
3. Update the metadata in the **Project Notes** sidebar.
4. Add images, reports, repositories, or demos later if you decide to introduce assets.

### Experience

Experience entries are in the `experience` section as timeline items. Update dates, responsibilities, advisor information, lab affiliation, course links, and supervisor details as needed.

### Publications / Writing

The `publications` section is structured for:

- Journal papers
- Conference papers
- Preprints
- Institutional reports
- Technical notes
- Research articles

For each entry, include authors, year, title, status, venue, DOI, arXiv link, code link, or report link as appropriate.

### Skills

Skills are grouped in the `skills` section. Edit each `<section class="skill-group">` block to add, remove, or reorganize tools and technical areas.

### Contact Information

The contact section includes:

- Email: `iqureshi@ucmerced.edu`
- LinkedIn: `linkedin.com/in/istafa-qureshi`
- GitHub: `github.com/1staf-a`

## GitHub Pages Deployment

1. Create a new GitHub repository.
2. Upload `index.html`, `favicon.png`, `styles.css`, `script.js`, `README.md`, and the `projects/` folder to the repository root.
3. Commit the files.
4. Open the repository settings on GitHub.
5. Go to **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the branch that contains the files, usually `main`.
8. Select the root folder, usually `/`.
9. Save the Pages settings.
10. Wait for GitHub to publish the site.
11. Open the published GitHub Pages URL and verify navigation, links, and mobile layout.

## Local Preview

Open `index.html` directly in a browser. The site does not require a development server.

## Future Improvements

- Add a downloadable resume or CV.
- Add a dedicated publications database or BibTeX section.
- Add project screenshots, figures, videos, or simulation result images.
- Add a research gallery for CFD, FEA, and visualization outputs.
- Add a technical writing or notes section.
- Add a dark/light theme toggle.
- Add a separate CV page.
- Add academic service, mentoring, and teaching pages.
- Add project detail pages if the portfolio grows beyond a single-page layout.

## Content Integrity

The site should only include verified information. Do not invent publications, awards, employers, advisors, dates, grants, patents, certifications, or links. Omit details until they can be confirmed.
