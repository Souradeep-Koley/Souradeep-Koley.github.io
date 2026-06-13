# Personal Academic Website Template

A clean 5-page placeholder site: Home (with news feed), Teaching, Research, Publications, and Other.

## Structure
```
index.html          Home (news feed + bio)
teaching.html
research.html
publications.html
other.html
assets/style.css     Shared stylesheet
```

## How to use
1. Replace "Your Name", tagline, email, and sidebar links in every page (search for "YN", "Your Name", "you@university.edu").
2. Fill in the placeholder boxes (dashed borders) on each page with your real content.
3. Add a profile photo: replace the `.avatar` div with an `<img>` tag if desired.

## Publishing on GitHub Pages
1. Create a new GitHub repository (e.g. `your-username.github.io` for a root site, or any name for a project site).
2. Push these files to the repository root (or to a `/docs` folder).
3. In the repo settings, go to **Pages** and set the source branch/folder.
4. Your site will be live at `https://your-username.github.io/` or `https://your-username.github.io/repo-name/`.

## Customizing the look
Colors, fonts, and layout are all defined in `assets/style.css` via CSS variables at the top of the file — change `--ink`, `--paper`, `--clay`, `--slate`, `--sage` to adjust the palette.
