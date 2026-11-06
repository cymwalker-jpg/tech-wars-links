# GitHub Pages URL Masking – Tech Wars Links

These folders contain ready-to-use redirect pages for the Tech Wars links.

## Folder structure
```
github-redirects/
├── setup/index.html    → first-time setup
├── signin/index.html   → everyday sign-in
├── me/index.html       → my points
├── stepup/index.html   → managers Step Ups
└── tv/index.html       → warehouse TV board
```

## How to deploy on GitHub Pages

1. Create a new public GitHub repository (example name: `tech-wars-links` or anything you prefer).
2. Upload the entire contents of the `github-redirects` folder into the root of the repo (so the folders `setup`, `signin`, `me`, `stepup`, and `tv` sit at the top level).
3. Go to the repo → **Settings** → **Pages**.
4. Under “Build and deployment” → Source: choose **Deploy from a branch**.
5. Branch: `main` (or `master`), Folder: `/ (root)`, then Save.
6. Wait 1–2 minutes. Your masked links will be:

| Purpose                  | Masked / Display Link                          |
|--------------------------|------------------------------------------------|
| First-time setup         | `https://YOURUSERNAME.github.io/REPO/setup/`   |
| Everyday sign-in         | `https://YOURUSERNAME.github.io/REPO/signin/`  |
| My points                | `https://YOURUSERNAME.github.io/REPO/me/`      |
| Managers: Step Ups       | `https://YOURUSERNAME.github.io/REPO/stepup/`  |
| Warehouse TV board       | `https://YOURUSERNAME.github.io/REPO/tv/`      |

Replace `YOURUSERNAME` and `REPO` with your actual GitHub username and repository name.

## Optional: Custom domain
If you own a domain, you can point it at the GitHub Pages site for cleaner links (e.g. `links.yourdomain.com/setup`).

All pages use both meta refresh and JavaScript so the redirect is fast and reliable.
