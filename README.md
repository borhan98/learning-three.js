# learning-three.js

This repository is a workspace for multiple Three.js learning projects. Each project lives in its own folder (for example `l1/`) and can have its own tooling/files.

## Structure

- `l1/` — lesson/project 1
- `.gitignore` — common ignores for all projects (keeps things like `node_modules/` and build outputs out of Git)

## Getting started

### l1

From the repo root:

```bash
cd l1
npm install
npm run dev
```

If `npm run dev` is missing, add scripts to `l1/package.json`, for example:

```json
{
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  }
}
```

## Adding new projects

Create a new folder (e.g. `l2/`, `shaders/`, `experiments/`) and keep any project-specific ignores inside that folder as needed.
