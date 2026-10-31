# SQL Gym

A free, browser-based SQL practice website.

## Deploy with GitHub Pages

1. Sign in to GitHub and create a **new public repository** named `sql-gym`.
2. On the repository page, choose **Add file → Upload files**.
3. Upload `index.html` from this folder and `README.md`.
4. Commit the files to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Choose branch **main** and folder **/(root)**, then click **Save**.
8. Wait for the deployment to finish. Your site URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/sql-gym/`

## Notes

- The site is a static HTML page and does not require a server.
- The full SQLite engine loads from a CDN. If that CDN is unavailable, the page has a limited starter SQL engine as a fallback.
- After changing the site, upload the updated `index.html` and commit the change to redeploy.
