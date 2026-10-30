<!-- BEGIN:nextjs-agent-rules -->

## This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->

## Energy Insights design contract

- Read `docs/design-system.md` before making UI changes.
- Treat `src/app/globals.css` as the source of truth for token values. Use semantic color utilities instead of hardcoded colors or Tailwind palette colors in product UI.
- Use Tailwind's default spacing scale, typography scale, and breakpoints. Build mobile-first.
- Keep the application light-mode only until a complete dark theme is explicitly approved.
- Preserve visible keyboard focus, WCAG AA contrast, non-color cues, and reduced-motion preferences.
- Add reusable UI abstractions only when supported by real, repeated use cases.
