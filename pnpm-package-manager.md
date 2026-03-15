# Use pnpm for package management and dev servers

In the Ethos workspace (and in worktrees), use **pnpm** for dependencies and local dev:

- **Install:** `pnpm install` (not `yarn` or `npm install`)
- **Add/remove:** `pnpm add <pkg>`, `pnpm add -D <pkg>`, `pnpm remove <pkg>`
- **Scripts:** `pnpm run <script>` or `pnpm <script>` (e.g. `pnpm start`, `pnpm test`)
- **Dev servers:** run with pnpm from the right directory (e.g. `cd frontend && pnpm run start:main`)
- **Worktrees:** run pnpm from the worktree root or from `frontend/` (or other app dir) when installing or starting dev there.

Equivalents: `yarn` → `pnpm install`; `yarn add x` → `pnpm add x`; `yarn run script` → `pnpm run script`. Do not change CI, Makefiles, or Dockerfiles that use yarn/npm unless explicitly asked.
