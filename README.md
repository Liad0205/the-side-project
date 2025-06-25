# Technical Blog with GitHub Pages

This project is a statically generated technical blog using pre-built HTML files, hosted on GitHub Pages.

## How it works

- All HTML, CSS, and asset files are served as-is (no static site generator required).
- The `.nojekyll` file disables Jekyll processing, so files and folders starting with `_` are not ignored.

## How to deploy

1. Push this repository to GitHub.
2. Go to the repository's **Settings > Pages**.
3. Under **Source**, select the branch (e.g., `main`) and `/ (root)` as the folder.
4. Save. Your site will be published at `https://<username>.github.io/<repo>/`.

## Add your content

- Add more HTML files for new posts or pages.
- Update `index.html` as your homepage.

---

For more, see the [GitHub Pages documentation](https://docs.github.com/en/pages/quickstart).
