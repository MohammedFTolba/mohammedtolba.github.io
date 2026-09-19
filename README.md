# Mohammed Farrag Tolba — Academic Homepage

A responsive, dependency-free academic and professional website prepared for GitHub Pages. It is designed for AI-hardware research, computer-architecture, FPGA/ASIC, RTL, and research-engineering opportunities.

## Publish on GitHub Pages

1. Create a public GitHub repository named exactly `mohammedtolba.github.io`.
2. Upload everything in this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will publish the website at `https://mohammedtolba.github.io/`.

If you use another repository name, the address becomes `https://mohammedtolba.github.io/<repository-name>/`.

## Files to edit later

- `index.html`: biography, research, publications, dates, and links.
- `assets/css/style.css`: colors, typography, and responsive layout.
- `assets/js/main.js`: mobile navigation, theme switching, active-section highlighting, reveal animation, and footer year.
- `assets/images/`: profile photograph, award images, favicon, and social preview.

## Profile photograph

The homepage uses `assets/images/mohammed-tolba-profile.webp`. To replace it later, export another portrait with the same filename or update the image path in `index.html`.

## Local preview

Run this command from the website folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Privacy

The public site includes the university email address but intentionally omits the phone number.
