# Mural Memory — published site files

This public repository contains the built static website only. The source project remains in the private [`mural-memory-demo`](https://github.com/baditaflorin/mural-memory-demo) repository.

Live demo: <https://baditaflorin.github.io/mural-memory-demo-site/>

The 30 mural variants are derived from the supplied CitiZenit photo. The painted facade is extracted, color and surface-flow treatments are applied to those real pixels, then placed back into the same photo. The former separate portrait asset is not part of this site. The original photo and extracted facade are available at the repository root.

GitHub Pages serves this branch from its root folder, so a push to `main` publishes the static files without a workflow. To update it, rebuild the app with `VITE_BASE_PATH=/mural-memory-demo-site/ npm run build` in the source repository, replace the built assets at the repository root, and push to `main`.
