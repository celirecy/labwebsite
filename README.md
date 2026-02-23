# Chin-Yee & Hsia Hematology Research Lab — Website

This repository contains the source code for the official website of the **Chin-Yee & Hsia Hematology Research Lab** at Western University, London, Ontario.

🌐 **Live site:**

---

## About the Lab

The Chin-Yee & Hsia Hematology Research Lab bridges insights between the clinical laboratory and the bedside to transform patient care. Our research focuses on:

- Early identification of rare hematologic diseases (PNH, immune cytopenias, unexplained cytopenias)
- AI-driven biomarkers and clinical decision support
- Clonal evolution in PNH and bone marrow failure syndromes

---

## Site Structure

```
/
├── index.html          # Home / landing page
├── about.html          # About the lab
├── research.html       # Research pillars and focus areas
├── team.html           # Team members and bios
├── publications.html   # Publications list
├── contact.html        # Get involved / contact form
└── README.md           # This file
```

All pages are **fully self-contained** — CSS is inlined and images are loaded from absolute URLs. No build tools or dependencies are required.

---

## How to Update the Site

### Editing a page
1. Click on the file you want to edit (e.g. `team.html`)
2. Click the **pencil icon** (✏️) in the top-right to edit
3. Make your changes
4. Scroll down and click **"Commit changes"**
5. The live site will update within 1–2 minutes

### Adding a new team member
Open `team.html` and find the `members-grid` section. Copy an existing `member-card` block and update the name, role, and image URL.

### Updating publications
Open `publications.html` and add a new `pub-item` block under the relevant PI section. Follow the existing format:

```html
<div class="pub-item">
  <span class="pub-year-tag">2025</span>
  <div class="pub-title">Title of the paper</div>
  <div class="pub-authors"><strong>Author A</strong>, Author B, et al.</div>
  <div class="pub-journal">Journal Name. Year;vol(issue):pages</div>
</div>
```

### Replacing an image
Images are currently loaded from the existing GitHub repository URLs. To use new images:
1. Upload the image file to the `images/` folder in this repo
2. Update the `src` attribute in the relevant HTML file to use the relative path, e.g. `src="images/newphoto.jpg"`

---

## Deployment

This site is hosted via **GitHub Pages**.

To enable GitHub Pages (if not already active):
1. Go to **Settings → Pages**
2. Under **Branch**, select `main` and folder `/ (root)`
3. Click **Save**

The site will be available at `https://<your-username>.github.io/<repo-name>/`

---

## Contact

For questions about the website, contact the lab at:
- 🏛️ Western University, Department of Medicine
- 🏥 London Health Sciences Centre, London, Ontario

© 2025 The Chin-Yee & Hsia Hematology Research Lab
