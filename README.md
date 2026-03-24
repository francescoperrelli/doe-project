# JupyterLite PB Demo

This is a minimal JupyterLite repository for hosting a notebook that reproduces the Plackett–Burman screening and ANOVA calculations from the presentation.

## Quick deploy

1. Create a new repository from the official JupyterLite demo template.
2. Replace the template `contents/` folder with the `contents/` folder from this package.
3. Replace or simplify `requirements.txt` with the one included here.
4. Commit to `main`.
5. In GitHub:
   - enable Actions
   - in Settings -> Pages, set Source to **GitHub Actions**
   - if needed, in Settings -> Actions -> General, allow **Read and write permissions**
6. After the workflow finishes, your site will be at:
   `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`

The notebook opens inside JupyterLite in the browser.
