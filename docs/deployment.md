# GitHub Deployment Notes

## Target

- Recommended repository name for a user site: `<github-username>.github.io`
- Expected URL: `https://<github-username>.github.io/`
- Repository visibility requested: private
- Site source: repository root
- Deployment method: GitHub Actions

## Important GitHub Pages Constraint

GitHub Pages is available from public repositories on GitHub Free. Publishing from a private repository requires GitHub Pro, GitHub Team, GitHub Enterprise Cloud, or GitHub Enterprise Server.

For a personal user site, the repository must be named exactly `<github-username>.github.io`. A differently named repository will publish as a project site at `https://<github-username>.github.io/<repository-name>/`.

## Setup Steps

1. Create a private GitHub repository named `<github-username>.github.io`.
2. Push this local repository to GitHub.
3. In GitHub, open repository Settings > Pages.
4. Set the source to GitHub Actions if it is not selected automatically.
5. Wait for the `Deploy GitHub Pages` workflow to complete.
6. Visit `https://<github-username>.github.io/`.

## Current Local Setup

- `.github/workflows/pages.yml` deploys the static site on pushes to `main`.
- `.nojekyll` disables Jekyll processing so GitHub serves the static files directly.
- `README.md` documents local preview and deployment requirements.
