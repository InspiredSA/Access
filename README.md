# Parent Access Registration Website

This is a simple static website for parents to access instructions for the school facial recognition access system. It is designed to work directly on GitHub Pages with no build tools or frameworks.

## File Structure

```text
/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── inspired-logo-wordmark copy.png
    ├── Reddam Register.pdf
    ├── Reddford Register.pdf
    ├── REDDAM VIDEO.mp4
    └── REDDFORD VIDEO.mp4
```

## Replace the Logo

Replace `assets/inspired-logo-wordmark copy.png` with the final school or Inspired Schools logo.

Keep the file name as `inspired-logo-wordmark copy.png` unless you also update the image path in `index.html`.

## Replace the Video

The page currently links to:

- `assets/REDDAM VIDEO.mp4`
- `assets/REDDFORD VIDEO.mp4`

For best results, use MP4 files that are compressed for web viewing. Keep these file names unless you also update the video paths in `index.html`.

## Replace the PDF

The page currently links to:

- `assets/Reddam Register.pdf`
- `assets/Reddford Register.pdf`

Keep these file names unless you also update the download links in `index.html`.

## Recommended Repository Name

Recommended repository name:

```text
parent-access-registration-guide
```

## Test Locally

Open `index.html` directly in a web browser.

The page is static, so it does not need a local server. The video and PDF will work once the final files have been added to the `assets` folder.

## Enable GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders.
3. Go to Settings.
4. Go to Pages.
5. Under "Build and deployment", select "Deploy from a branch".
6. Select the `main` branch and `/root`.
7. Save.
8. Wait for GitHub to publish the site.
9. Use the provided GitHub Pages URL to share with parents.

## Maintenance Notes

The site uses plain HTML, CSS, and JavaScript. Most text can be edited directly in `index.html`. Colours, spacing, and responsive layout rules are in `styles.css`. The FAQ accordion behaviour is in `script.js`.
