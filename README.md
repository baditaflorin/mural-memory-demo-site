# Mural Memory — published site files

This public repository contains the built static website only. The source project remains in the private [`mural-memory-demo`](https://github.com/baditaflorin/mural-memory-demo) repository.

Live demo: <https://baditaflorin.github.io/mural-memory-demo-site/>

GitHub Pages serves this branch from its root folder, so a push to `main` publishes the static files without a workflow. To update it, rebuild the app with `VITE_BASE_PATH=/mural-memory-demo-site/ npm run build` in the source repository, replace the built assets at the repository root, and push to `main`.
