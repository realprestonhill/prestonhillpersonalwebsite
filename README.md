# Preston Hill Site

This is a static website prepared for GitHub Pages deployment.

## Local structure

- `index.html`
- `about.html`
- `portfolio.html`
- `media.html`
- `gallery.html`
- `styles.css`
- `script.js`
- `assets/`

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to the repository.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, set `Source` to `GitHub Actions`.
5. Push to your default branch.
6. GitHub will publish the site automatically using the workflow in `.github/workflows/deploy.yml`.

## Notes

- The site uses relative links, so it works well on GitHub Pages.
- `.nojekyll` is included so GitHub Pages serves the site as plain static files without Jekyll processing.
