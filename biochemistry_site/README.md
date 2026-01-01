Biochemistry Study Guide — static site

Open the site locally by opening `index.html` in a browser, or run a simple HTTP server:

PowerShell:

```powershell
# from the repository root
python -m http.server 8000
# then open http://localhost:8000/biochemistry_site/index.html
```

Or use any static-file server. The site is intentionally minimal and static so you can edit the lesson pages under `biochemistry_site/lessons`.

Deploying to GitHub Pages

- Create a repository on GitHub and push this project.
- This repo includes a GitHub Actions workflow that publishes the `biochemistry_site` folder to the `gh-pages` branch on pushes to `main`.
- After pushing, enable GitHub Pages in the repository settings (Source: `gh-pages` branch or the Pages settings will point automatically).

If you want to deploy elsewhere (Netlify, Vercel), you can point those services to the `biochemistry_site` folder or drag-and-drop the folder into their dashboard.
