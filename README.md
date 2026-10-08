# Mural Memory — published site files

This public repository contains the built static website only. The source project remains in the private [`mural-memory-demo`](https://github.com/baditaflorin/mural-memory-demo) repository.

Live demo: <https://baditaflorin.github.io/mural-memory-demo-site/>

The site is deployed from `site/` by GitHub Actions. To update it, rebuild the app with `VITE_BASE_PATH=/mural-memory-demo-site/ npm run build` in the source repository, replace `site/` with the new `dist/` contents, and push to `main`.
