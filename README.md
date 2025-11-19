# Rabjanyane Sephetho — Acceptance Final POE

Short static website for the Rabjanyane Sephetho project (acceptance POE).

**Project type:** Static site (HTML, CSS, JavaScript)

**Overview**

This repository contains a small static website used for the Rabjanyane Sephetho Acceptance Final POE. It includes a set of HTML pages, styles, and JavaScript for lightbox/gallery functionality.

**Contents**

- `About us.html` — About page
- `Enquiry.html` — Enquiry/contact page
- `Gallery.html` — Gallery page
- `Get Involved.html` — Volunteer/get involved page
- `Home page.html` — Landing/home page
- `Our work.html` — Projects/our work page
- `css/` — Stylesheets (bootstrap/theme and template styles)
- `js/` — JavaScript files (jQuery, bootstrap, lightbox, etc.)
- `style/` — Additional style assets
- `wede/` — (project folder — keep as-is)

**Preview / Run locally**

Option 1 — Open in your browser
- Double-click any `.html` file (for example `Home page.html`) or right-click → Open with → your browser.

Option 2 — Serve over a local HTTP server (recommended for correct relative asset loading)

Windows / PowerShell (requires Python 3):

```powershell
cd "c:\Users\Magoshi\OneDrive - ADvTECH Ltd\Desktop\Rabjanyane Sephetho Acceptance Final POE"
python -m http.server 8000
```

Then open `http://localhost:8000/` in your browser.

Alternative: If you have Node.js installed, from the project root you can run a lightweight server such as `npx http-server`.

**Notes**
- The project is a plain static site — there are no build steps or external package managers required.
- If any images or assets are missing, check the `css/`, `js/`, and `style/` folders for referenced files.

**Contributing / Edits**

- Make small edits directly to the HTML/CSS/JS files.
- If you reorganise files, update paths in the HTML head/footer to maintain links to CSS/JS assets.

**License & Author**

Add a license and author information here (e.g., MIT) if you want to redistribute or publish this project.

---
Generated README for convenience. If you want a different structure or to include screenshots, I can update this file.
