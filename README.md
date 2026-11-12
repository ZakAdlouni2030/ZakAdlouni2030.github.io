# Zakariya Adlouni — portfolio

A lightweight, static portfolio for GitHub Pages. It uses plain HTML, CSS, JavaScript, and locally stored SVG illustrations; there is no build step, backend, or paid service.

## Publish this site

The repository `ZakAdlouni2030.github.io` already exists. If you are using a fresh clone of it, open a terminal in the project folder and run:

```bash
git add .
git commit -m "Build portfolio website"
git push -u origin main
```

If you are starting from a folder that is not already a clone, create a repository named **ZakAdlouni2030.github.io** under the GitHub account **ZakAdlouni2030**, then either upload these project files in the browser or clone the repository and copy the files into it. Keep `index.html` at the repository root. For a new local Git setup:

```bash
git init -b main
git add .
git commit -m "Build portfolio website"
git remote add origin https://github.com/ZakAdlouni2030/ZakAdlouni2030.github.io.git
git push -u origin main
```

### Enable GitHub Pages

1. Open the repository on GitHub and choose **Settings** → **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then click **Save**.
4. GitHub will publish the root-level `index.html` and the linked `assets/` files. Open **Settings** → **Pages** again to check the build status and use **Visit site** when deployment is ready.

The expected address is **https://zakadlouni2030.github.io/**. Because the repository name is exactly `USERNAME.github.io`, this is a user site, and the repository name does not add another path segment. A normal project repository instead uses `https://USERNAME.github.io/REPOSITORY-NAME/`; its repository name is a path, not a standalone domain.

### Keep it up to date

Edit `index.html` for page content, `assets/css/styles.css` for appearance, and `assets/js/main.js` for interactions. Keep image and file references relative (for example, `assets/images/project-1.svg`) so they work on the local site and GitHub Pages. To update the site, save your changes and run:

```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Pages can take several minutes to show a new deployment. If it does not appear, check the latest Pages build in the repository's **Actions** tab and confirm Pages is set to **main** and **/(root)**. For missing images or a broken résumé link, check spelling, letter case, and the path in `index.html`; GitHub Pages paths are case-sensitive. Keep the résumé file and its link in sync, and confirm the file loads before publishing.

## Images and résumé

The current illustrations are custom SVG artwork, not personal photographs:

- `assets/images/hero-circuit.svg` — hero graphic.
- `assets/images/project-1.svg` — solar e-bike charging and lock system diagram.
- `assets/images/project-2.svg` — ultrasonic sensor sweep diagram.
- `assets/images/favicon.svg` — browser tab icon.

No portrait or university photograph was supplied, so the design does not imply that an unrelated photo is Zakariya. Optional images can be added later under `assets/images/` and referenced by their exact filenames and extensions.

The résumé PDF is intentionally not included yet. The supplied copy contains personal contact details; only add a public-ready version after reviewing and approving it. Save the approved PDF as `assets/resume.pdf`, then replace the pending résumé message in `index.html` with a preview (`<iframe title="Résumé preview" src="assets/resume.pdf">`) and a direct link to `assets/resume.pdf`. Do not overwrite the supplied original.

## Public access and privacy

GitHub Pages websites are publicly accessible. A public repository also exposes its source files and any résumé or images stored in it. Review all content and files before pushing them. The supplied résumé PDF is not present in this starter site.

## Custom domain (optional)

If you own a separate domain, you can connect it by following GitHub's current [custom domain instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site). Configure the domain in **Settings** → **Pages** and add the DNS records required by your domain provider.
