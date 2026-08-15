# nexus-lab-org.github.io

Org-root GitHub Pages site. Served at `https://nexus-lab-org.github.io/` and,
via [nexuslab-router](https://github.com/nexus-lab-org/nexuslab-router)'s
pass-through proxy, at `https://nexuslab.in/`.

Plain static `index.html`, no build step. Add a card to the `.grid` in
`index.html` whenever a new project ships with GitHub Pages enabled.

## Publish

1. Create the `nexus-lab-org.github.io` repo on GitHub (must match that exact
   name for GitHub Pages to serve it at the org root).
2. Push this directory to it.
3. In the repo's Settings → Pages, set the source to the `main` branch, root.
