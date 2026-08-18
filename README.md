# Marathi Newsletter Monitor Web Page

## GitHub + Netlify setup

1. Create a new GitHub repository, for example `marathi-newsletter-monitor`.
2. Upload `index.html` and `organizations.json`.
3. Commit the files.
4. In Netlify choose **Add new project / Import an existing project**.
5. Connect GitHub and select `marathi-newsletter-monitor`.
6. Build command: leave blank.
7. Publish directory: `/` (or the repository root).
8. Deploy.
9. Netlify will provide a public URL.

## Updating data

Edit `organizations.json` in GitHub. Commit the change. Netlify automatically redeploys.

## Python monitor

Keep the Python monitor in a separate repository/folder initially. Its Excel report is the source for reviewing newly detected publications. After the first successful scan, the monitor can be extended to update `organizations.json` automatically.
