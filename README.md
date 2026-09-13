# LIPlay - Smart Audio Studio

GitHub Pages-ready Progressive Web App package.

## Upload to GitHub
Upload the **contents of this folder** to the root of your `LiPlay` repository, so `index.html` is directly in the repository root.

Required structure:

```text
LiPlay/
├── index.html
├── manifest.json
├── sw.js
├── .nojekyll
├── README.md
└── icons/
    ├── icon-192.png
    ├── icon-512.png
    └── icon-maskable.png
```

`index.html` contains the complete LIPlay application and does not depend on a missing `js/bundle.js` file.

## GitHub Pages
Set GitHub Pages to deploy from the `main` branch using the repository root, or use the included GitHub Actions workflow if your repository already has one.

After deployment, open the Pages URL and do a hard refresh (`Ctrl+F5`) if an older version was previously installed.
