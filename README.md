# Ankita Bhadane — Portfolio

Personal portfolio and resume site for **Ankita Bhadane**, Cloud / DevOps Engineer.

## Live Site

After enabling GitHub Pages, the site will be available at:

**https://ankitaworksataress.github.io/profile/**

> For a root URL like `https://ankitaworksataress.github.io`, rename this repository to `ankitaworksataress.github.io`.

## Deploy to GitHub Pages

1. Push this repository to GitHub (`ankitaworksataress/profile`).
2. Go to **Settings → Pages** in the repository.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **main** and folder **/ (root)**.
5. Save — the site will be live in a few minutes.

## Local Preview

```bash
cd profile
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080) in your browser.

## Structure

```
profile/
├── index.html          # Main portfolio page
├── css/style.css       # Styles
├── js/main.js          # Interactions & animations
└── assets/
    └── Ankita_Bhadane_CV.pdf
```

## Customize

Edit `index.html` to update content. Styles are in `css/style.css`. Replace `assets/Ankita_Bhadane_CV.pdf` when your resume is updated.
