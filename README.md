# Academic Website Scaffold

This folder now contains a basic academic website that is ready for GitHub Pages.

## What is included

- `index.html`: homepage with teaching-focused overview
- `teaching.html`: teaching philosophy, courses, and materials
- `research.html`: concise research page
- `cv.html`: readable CV summary page
- `contact.html`: contact page
- `404.html`: simple not-found page
- `styles.css`: complete site styling
- `script.js`: mobile navigation and footer year
- `.nojekyll`: keeps GitHub Pages from trying to process the site with Jekyll

## Best GitHub Pages setup

If you want the cleanest GitHub URL and do not have a personal domain, create a repository named:

`jadelintott.github.io`

That will publish the site at:

`https://jadelintott.github.io/`

If you use a different repository name, the site will instead live at:

`https://jadelintott.github.io/REPOSITORY-NAME/`

This site uses relative links, so it will work in either setup.

## Minimum GitHub steps

1. Create a new GitHub repository.
2. If possible, name it `jadelintott.github.io`.
3. Put all files from this folder into that repository.
4. Push to the `main` branch.
5. If GitHub Pages is not already live, go to `Settings` -> `Pages`.
6. Under `Build and deployment`, choose `Deploy from a branch`.
7. Select branch `main` and folder `/ (root)`.
8. Save and wait a minute or two.

## Easy things to replace first

Search for these placeholders and replace them:

- Department or program details
- Field or discipline details
- Research summary and materials
- CV, teaching statement, syllabi, and related PDFs

## Where to put materials later

- Headshot or photo: `assets/images/`
- CV PDF: `assets/cv/`
- Teaching statement, syllabi, assignments, or other PDFs: `assets/docs/`

## Local preview

If you want to preview it locally in a terminal:

```bash
python3 -m http.server 8000
```

Then open:

`http://localhost:8000`
