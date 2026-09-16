# D&D Wiki Sidebar Skeleton

This version uses the updated stylesheet and adds a persistent left sidebar.

## What was added

The original visual system is preserved. The CSS now includes a sidebar layout after the existing button rules:

- `.wiki-layout` — two-column page layout
- `.wiki-sidebar` — fixed/sticky left navigation area
- `.wiki-sidebar-title` — campaign/logo text
- `.wiki-sidebar-section` — small sidebar category headings
- `.wiki-sidebar-links` — simple secondary link lists
- `.wiki-content` — main article area
- A mobile media query that stacks the sidebar above the content below 700px

## Important

The original table and button styles remain usable. The navigation uses your `.button-1` and `.button-1.active` classes.

The Google Font imports are in the HTML because your CSS references Pixelify Sans, Silkscreen, and Jacquard 12.

## GitHub Pages

Upload the contents of this folder to a repository and enable GitHub Pages from the repository's Settings → Pages.

`index.html` is the homepage.
