# Dorhodo — personal website

Quarto website for `https://dorhodo.github.io/`.

## Publish

1. Create a **public** GitHub repository named exactly `dorhodo.github.io`.
2. Upload the contents of this project to the repository root (not the enclosing folder).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **GitHub Actions** as the source.
5. Push to the `main` branch. The workflow in `.github/workflows/publish.yml` will render and deploy the site.
6. Check the **Actions** tab for a successful `Publish site` run, then visit `https://dorhodo.github.io/`.

## Edit

- Home: `index.qmd`
- Profile: `about.qmd`
- Articles: add `.qmd` files under `articles/posts/`
- Slides: put PDFs under `slides/pdf/` and add links in `slides/index.qmd`
- Design: `styles.css`

## Preview locally

Install Quarto, then run:

```bash
quarto preview
```

To render without preview:

```bash
quarto render
```

Before publishing, replace or remove the sample article and fill in the About page. Only publish material you have permission to share.
