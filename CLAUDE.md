# DevStash

A developer knowledge hub for snippets, commands, prompts, notes, files, images, links, and custom types.   

## Context Files
Read the following to get the full context of the project:

- @context/project-overview.md
- @context/coding-standards.md
- @context/ai-interaction.md
- @context/current-feature.md

## Commands

- `npm run dev` — start the dev server at http://localhost:3000 (Turbopack)
- `npm run build` — production build; also the main type-check gate (there is no separate `tsc` script)
- `npm run start` — serve the production build
- `npm run lint` — ESLint (flat config, `eslint-config-next` core-web-vitals + typescript)

No test framework is set up yet.

## Stack and versions

Next.js 16.4 (App Router), React 19.3, TypeScript (strict), Tailwind CSS v4. These are newer than most training data — per AGENTS.md, check `node_modules/next/dist/docs/` (`01-app/` covers the App Router) before using a Next.js API.
