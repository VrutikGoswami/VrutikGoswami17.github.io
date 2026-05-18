# Vrutik Goswami Portfolio

Static personal portfolio for GitHub Pages. The site uses plain HTML, CSS, and vanilla JavaScript only.

## Structure

```text
site/
|-- index.html
|-- about.html
|-- projects.html
|-- zyft-health.html
|-- handrail.html
|-- writing.html
|-- creatine.html
|-- resume.html
|-- contact.html
|-- 404.html
|-- robots.txt
|-- sitemap.xml
|-- .nojekyll
|-- README.md
`-- assets/
    |-- css/styles.css
    |-- js/main.js
    `-- RESUME_VRUTIK.pdf
```

## Deploy to GitHub Pages

1. Create a repository named `<username>.github.io`.
2. Copy the contents of this `site/` folder into the repository root.
3. Commit and push to the `main` branch.
4. In GitHub, open Settings -> Pages.
5. Set Source to `Deploy from a branch`, branch to `main`, and folder to `/root`.
6. Replace `assets/RESUME_VRUTIK.pdf` with the final resume PDF.

## Custom Domain

Add a `CNAME` file at the repository root containing only your domain, for example:

```text
vrutikgoswami.com
```

Then add the matching DNS records with your domain provider and configure the custom domain in GitHub Pages settings.
