# Product Photo Resizer

A small browser app for preparing product photos for online listings. Choose a photo, set the output dimensions, and download the resized file. It runs locally in the tab with no dependencies, accounts, or uploads.

## Use it

Open `index.html` in a modern browser. In a project checkout that stores the app in `dist/`, open `dist/index.html` instead.

- Open a JPEG, PNG, or WebP photo.
- Choose a square, portrait, or landscape preset, or enter a custom width and height (1–4096 pixels each).
- Use **Crop to fill** for a centered crop or **Fit entire photo** to keep the whole image. Both preserve the photo’s proportions.
- Export JPEG, PNG, or WebP. JPEG fills any transparent areas with white. PNG and WebP preserve transparency. JPEG and WebP have adjustable quality.

The selected image is re-encoded by the browser, and WebP export depends on browser support.

## Publish on GitHub Pages

Upload `index.html`, `README.md`, and `LICENSE` to the root of a GitHub repository. In **Settings → Pages**, deploy from the root of your default branch.

## License

[MIT](LICENSE).
