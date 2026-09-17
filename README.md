# Cham QMagSpin Lab website

Starter Quarto website for the Quantum Magnonics & Spintronics group at NTU.

## 1. Install Quarto

Download Quarto from https://quarto.org/ and install it on your computer.

## 2. Preview locally

Open Terminal in this folder and run:

```bash
quarto preview
```

Quarto will open a local browser preview and automatically refresh as you edit files.

## 3. Edit the site

Main files:

- `_quarto.yml` — site title, navigation, footer, global settings
- `index.qmd` — homepage
- `research.qmd` — research themes
- `people.qmd` — group members
- `publications.qmd` — publications
- `news.qmd` — news
- `join.qmd` — recruitment
- `styles.scss` — all visual styling

Search for `YOUR_EMAIL` and replace it with your NTU email.

## 4. Add images

Put images in `assets/`, for example:

```text
assets/jerald.jpg
assets/research-magnon.jpg
assets/research-ultrafast.jpg
```

Then reference them in a `.qmd` file with:

```markdown
![](assets/research-magnon.jpg)
```

## 5. Publish to GitHub Pages

Create a GitHub repository, commit these files, and push to the `main` branch. This starter includes a GitHub Action in `.github/workflows/publish.yml` that renders and publishes the website to a `gh-pages` branch.

In GitHub:

1. Go to **Settings → Actions → General → Workflow permissions**.
2. Enable **Read and write permissions**.
3. Go to **Settings → Pages**.
4. Configure Pages to deploy from the `gh-pages` branch if GitHub does not select it automatically.

You can also publish once from your computer with:

```bash
quarto publish gh-pages
```

## 6. Add a custom domain later

Once you own a domain such as `qmagspinlab.com`, configure it in GitHub Pages settings. You do not need to decide the final domain before developing the site.

## Suggested first edits

1. Replace the email placeholders.
2. Add your portrait.
3. Adjust the homepage mission sentence.
4. Replace placeholder recruitment wording with your actual openings.
5. Add research figures once you decide which visuals best represent each theme.
