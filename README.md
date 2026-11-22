# Jestin Raj — Microsoft 365 Cinematic Portfolio (V5)

Interactive personal portfolio showcasing Microsoft 365 administration, modern workplace operations, an expandable career timeline, troubleshooting playbooks, RepairOS AI and AI-assisted product thinking.

## Preview

The complete V5 site is embedded in **`index.html`** — including its CSS, JavaScript, portrait image and resume PDF. No build step, package manager or API keys are required.

To view locally, open `index.html` in a modern browser or run:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish with GitHub Pages

1. Merge the portfolio pull request into `main`.
2. In repository **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, then save.
3. Wait for GitHub's deployment status to report success, then open the Pages URL shown there.

GitHub Pages may not yet be enabled. This repository contains a legacy `styles.css` file which the self-contained V5 index does **not** need.

## Main features

- Animated blue/violet network hero with a separate photo panel
- Searchable, filterable Microsoft 365 administration workload cards
- Operational examples for Entra ID, Exchange Online, Intune and Purview
- Career history based on the owner's submitted resume
- RepairOS AI concept workflow and project showcase
- AI-assisted workflow and product-thinking showcase
- Responsive layout, reduced-motion support and keyboard navigation
- Embedded downloadable resume

## Content and privacy

The site contains the owner's portrait, contact details and professional resume, intended for a publicly accessible portfolio. Review these details before merging to a public branch or enabling Pages.

Operational examples are illustrative; they are not live tenant connections or customer case records. RepairOS AI is shown as a project in development. Verify all professional responsibility descriptions before public publication.

## Source maintenance

This commit uses the self-contained HTML preview for portability. To continue larger-scale editing, use the original separately structured V5 source package (`index.html`, `styles.css`, `script.js`, `assets/`) from the ChatGPT build conversation and replace this bundled preview with those files.
