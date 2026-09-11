# Jensen Feng — Engineering Portfolio

Static HTML and CSS. No dependencies or build step required.

## Publish on GitHub Pages

1. Create a public repository named `jfeng06.github.io` under `jfeng06`. If it already exists, inspect its contents before replacing anything.
2. Upload this folder's contents to the repository root, including assets, docs, and projects. Do not upload the ZIP itself.
3. Open Settings → Pages. Select Deploy from a branch, then main and /(root), and save.
4. Once the Pages deployment succeeds, the address will be https://jfeng06.github.io/.

This package has not been pushed or published on GitHub yet.

## Editing guide

| File | Purpose |
| --- | --- |
| index.html | Introduction, About, and project summaries |
| style.css | Colors, fonts, spacing, and mobile layout |
| projects/traffic-signaling/index.html | Traffic signal case study |
| projects/studytrack/index.html | Occupancy detector case study |
| projects/audio-equalizer/index.html | Equalizer case study |
| projects/risc-v/index.html | Processor case study and status |
| docs/ | Downloadable PDF reports |
| assets/ | Project images |

Edit a file in GitHub using the pencil icon, then commit the changes. Once branch publishing is enabled, commits to main trigger updates. Alternatively, clone the repository and edit with VS Code.

Update both the homepage summary and case study when changing a project status. Headers and footers are repeated in each HTML file. Keep PDF filenames unchanged when replacing reports to preserve links.

To add a project, copy an existing project folder, update its content, and add a homepage card.

## Local preview

From the folder containing index.html, run:

```sh
python -m http.server 8000
```

Open http://localhost:8000. Use a server rather than opening the HTML file directly because links start at the site root.

## Hosting notes

Root-relative links are ready for jfeng06.github.io or a custom domain. Hosting under a repository subpath requires adjusting those links.

All three reports become public downloads when published. No analytics, forms, external JavaScript, or API keys are included. The original hosted portfolio remains separate.
