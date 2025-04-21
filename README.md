# shadcn-demo
Minimal [shadcn](https://ui.shadcn.com/) starter/demo with buttons and a dark mode toggle.

- Uses react v19, tailwind v4, and pnpm.
- Started with [manual](https://ui.shadcn.com/docs/installation/manual) install, because shadcn does not play nice (see [#4746](https://github.com/shadcn-ui/ui/issues/4746)) when the root tsconfig uses references to other tsconfigs, as in `create vite...`.
- Copied root tsconfig, and a few other things from [cloudflare/agents-starter](https://github.com/cloudflare/agents-starter).
- Note that this repo has no pnpm lockfile - set `packageManager:` to pnpm in package.json or else the shadcn cli will assume npm and get very unhappy.

### UI todos
- [] Fix the colors (red and black are not nice).
- [] Use a proper menu component.
- [] Replace darkmode dropdown with a simple toggle.

### Cloudflare todos
- [] Add wrangler config and deploy to Cloudflare.

### Vercel todos
- [] Add vercel config and deploy to Vercel.
- [] Try linking to v0.

### Test todos
- [] add vitest and basic tests.
- [] add a pattern for e2e tests.