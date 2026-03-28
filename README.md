# website-portfolio-immo

Minimal Hugo template for portfolio-immo.ch with GitHub Pages deployment.

## Run locally

1. Install Hugo (extended version).
2. Start dev server:

	hugo server -D

## Deploy with GitHub Actions

The workflow is in `.github/workflows/hugo.yml`.

1. Push to the `main` branch.
2. In GitHub repository settings:
	- Go to Pages.
	- Set Source to GitHub Actions.
3. Configure DNS for `portfolio-immo.ch` to point to GitHub Pages.

The custom domain is declared in `static/CNAME`.