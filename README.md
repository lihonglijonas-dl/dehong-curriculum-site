# A Future-focused Curriculum and Assessment Model for Junior Secondary Chinese at Xi'an Dehong

Single-page static microsite scaffold for a postgraduate education assignment website. This version is intentionally a deployable structure rather than a completed academic argument. It provides the full page layout, responsive navigation, placeholder sections, academic tables, timeline elements, and acknowledgement boxes so that revised content can be inserted later without rebuilding the interface.

## Project Purpose

This microsite is designed to present an academic design proposal with a clean, credible, non-promotional layout. It avoids unverified claims, does not imply access to internal school documents, and does not claim that Xi'an Dehong has already implemented the proposed model.

Use this scaffold to:

- Insert the final thesis and section text.
- Replace placeholders with verified evidence and approved wording.
- Add checked references once citation details are confirmed.
- Deploy a lightweight academic website without a framework or backend.

## File Structure

```text
.
├── index.html
├── styles.css
├── script.js
└── README.md
```

- `index.html`: Semantic single-page microsite with all required sections and placeholders.
- `styles.css`: Academic visual system, responsive layout, cards, tables, timeline styling, and accessibility-focused spacing/contrast.
- `script.js`: Minimal JavaScript for mobile navigation toggle and active section highlighting.
- `README.md`: Project overview and usage notes.

## How to Preview Locally

Because this is a plain static site, you can preview it in any browser.

Option 1:

- Open `/Users/lihongli/Documents/dehong-curriculum-site/index.html` directly in a browser.

Option 2:

- Run a simple local static server from the project directory, for example:

```bash
python3 -m http.server 8000
```

- Then open `http://localhost:8000`.

## How to Deploy

This project can be deployed to any static hosting service, including:

- GitHub Pages
- Netlify
- Vercel static deployment
- Cloudflare Pages
- School or university static hosting

Deployment steps are generally:

1. Upload the contents of this folder.
2. Set `index.html` as the entry page if your host asks.
3. No build step is required.
4. No environment variables, database, or server setup are required.

## Where Final Content Should Be Inserted

Replace placeholder text directly in `index.html`.

Key areas to complete:

- `#home`: final thesis statement and refined introductory wording
- `#context`: revised Section 2 rationale cards
- `#evidence`: completed evidence matrix
- `#frameworks`: framework discussion and design tensions
- `#principles`: reform principle explanations
- `#model`: model explanation, examples, assessment structure, and AI boundary
- `#unit`: example unit details, sequence, success criteria, and risk controls
- `#outcomes`: outcome-evidence matrix
- `#references`: portfolio evidence map and verified reference list

## Content Guardrails

When replacing placeholders:

- Do not invent citations.
- Do not add unverified school facts.
- Do not claim Xi'an Dehong has implemented the proposed model.
- Do not claim access to internal school documents, rubrics, grading systems, or student data.

## Accessibility and Layout Notes

The scaffold includes:

- Semantic HTML structure
- A skip-to-content link
- Fixed top navigation with anchor links
- Responsive card and grid layouts
- Horizontally scrollable tables on smaller screens
- High-contrast text with a restrained accent colour
- Minimal JavaScript only where needed for usability

## Next Suggested Step

The next practical step is to replace the section placeholders in `index.html` with your approved academic wording and verified evidence, then do one content-editing pass for consistency of terminology across the model, unit, outcomes, and references sections.
