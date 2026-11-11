<!-- BEGIN:nextjs-agent-rules -->

## This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->

## shadcn/ui

When working with shadcn/ui components, configuration, or design systems, read and follow `.agents/skills/shadcn/SKILL.md` and its linked reference files before making changes. Use the project's `npx shadcn@latest` CLI for shadcn operations, check the project context and component docs, and review generated files. To add all available shadcn/ui components, run `npx shadcn@latest add --all`. For migrations from Radix UI to Base UI, also follow `.agents/skills/migrate-radix-to-base/SKILL.md`.
