# SG Exercise Demo Project

This repository contains a front-end demo project originally created in 2019 as part of a job application. It showcases a lightweight static site workflow powered by Gulp for asset compilation and live development.

## Project Background

The codebase was written to demonstrate proficiency with client-side tooling, including modular JavaScript, Sass styling, asset optimization, and automated build tasks. While the project itself is simple, it highlights the ability to assemble a production-ready pipeline using the technologies popular at the time.

## Getting Started

1. **Install Node.js** – Use Node 16 or newer to ensure compatibility with the current Sass tooling.
2. **Install dependencies** – Run `npm install` in the project root.
3. **Start development** – Execute `npm run start` to build assets and launch the BrowserSync dev server.
4. **Create a production build** – Run `npm run production` to generate optimized output in the `prod/` directory.

## Repository Structure

- `src/` – Source JavaScript, Sass, and HTML partials.
- `tasks/` – Custom Gulp tasks for building and serving the project.
- `build/` – Generated development build (created during `npm run start`).
- `prod/` – Production-ready output (created during `npm run production`).

## Notes

Because this is a historical demo, some dependencies may produce warnings on install. The current configuration upgrades the Sass toolchain so it remains compatible with modern Node releases while preserving the original structure and intent of the project.
