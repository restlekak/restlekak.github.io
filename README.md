# eidolon Legal Documents

Privacy policies and legal documents for eidolon mobile applications, served via GitHub Pages at [restlekak.github.io](https://restlekak.github.io).

## Adding a new project

1. Copy the template: `cp -r _template PROJECT-SLUG`
2. Edit `PROJECT-SLUG/index.html` — replace all `PROJECT_NAME` and `DATE` placeholders
3. Add a card to `index.html` linking to the new page
4. Commit and push

## Structure

```
index.html          ← landing page (card grid of all projects)
style.css           ← shared styles
PROJECT-SLUG/       ← per-project folder
  index.html        ← privacy policy (Turkish + English)
_template/          ← template for new projects
```
