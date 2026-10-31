# Floorplan Studio 4

Browser-based floor planning, site design, heating and lighting analysis, and real-time 3D visualisation. Everything runs in the browser from a single `index.html`, so it can be hosted free on GitHub Pages.

## What's new in 4.0

- **Home page.** The app opens on a welcome page with **Start a new design** and **Continue editing**, and a navigation bar for Home, My Projects, Getting Started and About.
- **My Projects cards.** Each saved design shows a miniature floor plan, its floor and room counts, when it was last saved, and buttons to open it or download a JSON backup. You can search projects, create new ones, import a JSON file, or open the full project manager to copy, rename and delete designs.
- **Getting Started guide.** A four-stage walkthrough with a keyboard shortcut reference.
- **Home button.** Use the **Home** button in the editor's title bar, or File → Home, to return to your projects at any time without reloading.

- **Workspace.** A professional interface in dark (default) or light mode. Switch with the sun/moon button in the title bar or **View → Light interface**; your choice is remembered. It also has a menu bar (File, Edit, View, Insert, Analyse, Render, Help), a status bar with live coordinates, rulers along the drawing, and consistent line icons.
- **3D renderer.** Sun shadows positioned from the project's location, date and north orientation. The renderer adds sky lighting, tone mapping and atmospheric haze.
- **Visual styles.** Choose Realistic, Clay or Technical with outlines.
- **Cameras.** Perspective or orthographic, with an adjustable lens, smooth camera movement and a compass navigator.
- **Render 4K image.** Exports a high-resolution still with sharper shadows.

All earlier features and saved projects continue to work.

## Links

Sections can be linked directly: `#home`, `#projects`, `#start`, `#about`, and `#editor` to go straight to the editor.

## Run locally

Open `index.html` in a modern desktop browser. No build or installation is needed.

## Publish with GitHub Pages

1. Create a GitHub repository, or open your existing one.
2. Upload the **contents** of this package (`index.html`, `README.md`, `.nojekyll`) to the repository root. Do not upload the ZIP itself.
3. Commit to your default branch (usually `main`).
4. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select your default branch and **/(root)**, then save.
5. Visit the URL shown under **Settings → Pages** once it has deployed.

The app loads the IBM Plex Sans font from Google Fonts. If that is unavailable, it falls back to the system font. There are no other external dependencies and no backend.

## Saving projects

- **Save** and **Projects** store designs in this browser's local storage for the site's address. This is not cloud sync.
- **File → Export project (JSON)** creates a portable backup. Use **File → Import project** on another device or browser to load it.
- Projects saved while opening the file locally don't appear automatically on your GitHub Pages site, because the two addresses are separate. Move them with Export/Import JSON.
- Clearing site data or using private browsing can erase saved designs. Keep JSON backups of important work.

## Keyboard

Press `?` for the full list. Common shortcuts are `V` select, `R` rectangle room, `P` custom room, `D` door, `W` window, `M` measure, `G` toggle snap, `Ctrl+Z`/`Ctrl+Y` undo/redo, `Ctrl+S` save, `Ctrl+O` projects and `Ctrl+P` print layout.

## Important note

Floorplan Studio is for conceptual planning and visual experimentation. It does not produce construction-ready drawings, structural engineering, electrical design, or building-code certification.
