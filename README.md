# Oskar Hulter Dev Blog 📄

![AstroPaper](public/astropaper-og.jpg)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![GitHub](https://img.shields.io/github/license/satnaing/astro-paper?color=%232F3741&style=for-the-badge)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white&style=for-the-badge)](https://conventionalcommits.org)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=for-the-badge)](http://commitizen.github.io/cz-cli/)

## 🚀 Project Structure

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.

All blog posts are stored in `src/content/blog` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

- `pnpm install` - Installs dependencies
- `pnpm test` - Runs the playwright e2e tests
- `pnpm run dev` - Starts local dev server at `localhost:3000`
- `pnpm run build` - Build your production site to `./dist/`
- `pnpm run preview` - Preview your build locally, before deploying
- `pnpm run format:check` - Check code format with Prettier
- `pnpm run format` - Format codes with Prettier
- `pnpm run sync` - Generates TypeScript types for all Astro modules. [Learn more](https://docs.astro.build/en/reference/cli-reference/#astro-sync).
- `pnpm run cz` - Commit code changes with commitizen
- `pnpm run lint` - Lint with ESLint

## 📜 License

Licensed under the MIT License, Copyright © 2023

---

Based on the awesome paper template by [Sat Naing](https://satnaing.dev) 🙏

Made with 🤍 by [Oskar Hulter](https://oskarhulter.com) 👨🏻‍💻

