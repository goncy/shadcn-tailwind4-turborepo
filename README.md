# Monorepo with Shadcn/ui and TailwindCSS v4

This project includes a `web` project and a `docs` project. Both uses a different them based on `tailwindcss` v4.

There is a `ui` package that contains Shadcn components.

There is a `theme` package that defines the available themes.

The parent app (web and docs) define which theme to use.

## Gotchas

To add components to `ui` use `pnpm dlx shadcn@2.1.6 add <component>` it looks like alias resolution got broken after that version.