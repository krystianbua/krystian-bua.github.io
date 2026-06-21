# Krystian Bua academic website

Static academic website generated from the public Google Sites page and prepared for GitHub Pages.

## Structure

```text
.
├── index.html
├── assets/
│   └── styles.css
├── README.md
└── .nojekyll
```

## Deploy on GitHub Pages

1. Create a new GitHub repository, for example `krystian-bua.github.io` or `academic-website`.
2. Upload these files to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`.
6. Save. GitHub will publish the site after the first build.

## Local preview

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- The CV link points to the existing Google Drive PDF.
- The profile uses a text monogram placeholder (`KB`) instead of copying the Google Sites image. Replace it with an image in `assets/` if desired.
