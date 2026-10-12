# Laura Xing — Academic Website

A responsive, single-page academic portfolio, designed in the familiar Academic Pages style and ready for GitHub Pages. Plain HTML/CSS/JavaScript means **no Jekyll, Ruby, build command, or npm needed**.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `YOUR_USERNAME.github.io` (replace with your actual GitHub username).
2. Upload `index.html`, `styles.css`, `script.js`, and the `assets/` folder to the **root** of that repository, preserving folder names. The easiest route is GitHub → Add file → Upload files. Or use Git locally.
3. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select branch **main** and folder **/(root)**, then save.
4. Your site will appear at `https://YOUR_USERNAME.github.io/` after GitHub Pages deploys it.

## Customize before publishing

- `index.html`: update name as preferred, bio, research descriptions, exact publication title/authors, email, GitHub, Scholar, and LinkedIn URLs.
- Replace `assets/profile-placeholder.svg` with your actual photo, then change `<img src="assets/profile-placeholder.svg">` to the filename, e.g. `assets/profile.jpg`.
- Add your real CV at `assets/Laura_Xing_CV.pdf`. Until then, the CV button links to a missing file.
- The research illustrations are original CSS graphics, **not experimental data or project photographs**. Replace with your own photos if desired.
- `styles.css`: customize colors, typography, and spacing.

**Accuracy note:** The publication entry uses a descriptive placeholder title; check and replace with the authoritative manuscript title and full authorship before publishing. The IROS poster is listed as a research output rather than a peer-reviewed paper. Education/research timelines are initial drafts to verify.

## Test locally

Double-click `index.html` to preview, or use `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Optional: use the full Academic Pages theme instead

If you want its ready-made Jekyll publication/talk archives and blogging features, use https://github.com/academicpages/academicpages.github.io as a template. This lightweight version is independently implemented but follows a similar academic visual structure.
