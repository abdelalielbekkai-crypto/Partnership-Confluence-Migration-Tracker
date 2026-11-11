# Partnership Confluence Migration Tracker

A local-first tracker for the partnership-process migration from DW to Astro.
Single static page: no build step, no backend, no login, no network calls.

- Tabs: Dashboard, Pages, Process Mapping
- Data is saved in your browser's localStorage (per browser and per device)
- Open `index.html` directly, or host it on GitHub Pages

## Deploy on GitHub Pages
1. Create a new repository on GitHub (e.g. `migration-tracker`).
2. Upload `index.html` and `README.md` to the root of the repository.
3. Go to Settings > Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch", Branch to `main`, folder `/ (root)`, then Save.
5. Wait 1-2 minutes. The site is live at `https://<your-username>.github.io/<repo-name>/`.

## Notes
- Clearing browser site data erases the tracker data. Use Export CSV on the Pages and Process Mapping tabs to keep copies.
- Use a private repository only if your GitHub plan supports private Pages; otherwise the page is public (the page holds no data, since data stays in each visitor's browser).
