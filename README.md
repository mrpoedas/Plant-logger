# Site Log

A single-page app for logging maintenance visits — date, place, notes, and an "action required" flag — with a home feed of recent activity and a searchable archive.

## Use it locally
Just open `index.html` in any browser. No build step, no dependencies. Data is saved in that browser's local storage, so it stays on whatever device/browser you open it in.

## Host it for free with GitHub Pages
1. Create a new GitHub repo and upload `index.html` (and this README) to it.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, pick the `main` branch and `/ (root)` folder, then **Save**.
4. GitHub will give you a URL like `https://<your-username>.github.io/<repo-name>/` within a minute or two — open it and the app loads there.

Each visitor's data is local to their own browser on that device; it isn't shared between devices or people.
