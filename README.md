# About

A simple "Hello World" template with TypeScript, Docker, and ESLint pre-configured.

# Usage

Please run `pnpm up` to update dev-dependencies (eslint, ts-node-dev, and others).

Use this repository as a template for your project by copying with [github](https://github.com)'s UI or manually with `git clone`.

## With github.com UI

Please refer to [this page](https://docs.github.com/ru/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) for details

## Manually

```sh
git clone https://github.com/osipovts/skeleton.git
mv -R skeleton my_project
cd my_project
git remote remove origin
git remote add origin <YOUR REPO URL>
git push -u origin --all
git push -u origin --tags
```

# Run

- `pnpm build && pnpm start`: Compile TypeScript to JavaScript and run app
- `pnpm dev`: Run in "watch mode" for development
- `pnpm lint`: Run ESLint to check code style
- `pnpm lint:fix`: Allow ESLint to fix code

# Docker

- `docker compose -f docker-compose.dev.yml up`: Run in dev-mode
- `docker compose -f docker-composeprod.yml up`: Run in prod-mode
