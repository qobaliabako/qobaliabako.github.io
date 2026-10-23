# Bako Kobalia — Research & Writing

A static portfolio prepared for **qobaliabako.github.io**. It brings together research papers, behavioural experiments, academic writing and certificates.

## Publish on GitHub Pages

1. Use the GitHub account **qobaliabako**.
2. Create the public repository **qobaliabako.github.io**.
3. Upload the contents of this folder directly into the repository root. `index.html` must be at the top level.
4. In **Settings → Pages**, choose **Deploy from a branch**, **main**, **/ (root)**, then save.
5. Wait for the Pages deployment to succeed. The intended website address is `https://qobaliabako.github.io/`.

The `.nojekyll` file disables Jekyll processing. There is no build step, package installation, database or API key.

## Edit the portfolio

- `index.html`: biography, project descriptions, paper links, writing and certificates.
- `style.css`: colours, typography, layout, responsive and print styles.
- `script.js`: optional navigation highlighting. The site and all downloads work without JavaScript.
- Five project PDFs are stored alongside the page, using descriptive filenames.
- The original certificates are included as PDF or PNG files.
- The portrait, certificate previews and favicon are also in the repository root.

To add a paper, place its PDF in the repository root, copy a `<article class="paper">` block, and update the title, description, authors and file link. To add a certificate, copy a `<details class="certificate">` block. Always retain co-author credits and distinguish coursework, commentary, participation and course completion.

For a local preview, run `python3 -m http.server 4173` from this folder, then open `http://localhost:4173/`.

## Content and attribution

Content was prepared from the supplied portfolio folder, research notes and the portfolio update package supplied on 23 October 2026. The package updates the research collaboration, project contributions, role chronology, expected graduation, service and skills. These biographical details are supplied by the portfolio owner.

The five Mdevari interviews link to their original publications: <https://mdevari.ge/articles/7217/>, <https://mdevari.ge/articles/7065/>, <https://mdevari.ge/articles/6744/>, <https://mdevari.ge/articles/6685/> and <https://mdevari.ge/articles/6607/>. Each article’s byline explicitly credits Bako Kobalia. English titles are descriptive translations; the original Georgian titles are also shown. Co-authors are credited.

Color Clash remains hosted at its existing address. The two software repositories remain under Bako’s existing GitHub account; this portfolio does not modify either experiment.

The original project documents and certificates are included unchanged. Their authors retain their respective rights. No blanket software licence is applied to the writing, photographs or documents.

The broader Drive folder also contains application letters, academic records and other administrative documents. Those are not part of this website. The private review/download files and the older CV are not included.
