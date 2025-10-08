# Assets

Place static assets for the site in this folder.

Resume PDFs (multilingual):

- Add your English resume as `resume-en.pdf` (path: `src/assets/resume-en.pdf`).
- Add your French resume as `resume-fr.pdf` (path: `src/assets/resume-fr.pdf`).
- Add your German resume as `resume-de.pdf` (path: `src/assets/resume-de.pdf`).

The Resume page (`src/resume.html`) will embed and link to these files. The page defaults to English.

Company logos:

- Place company logos referenced on pages in this folder, for example `company1-logo.png` and `company2-logo.png`.
- Recommended size: provide a square PNG or SVG around 256x256px for best results; the site will display them at ~84x84px.

Notes:

- This folder is intentionally empty in the repo; add your files locally and commit if you want them tracked.
- If you're deploying to a hosting provider, ensure the `assets/` folder is served as static files.
