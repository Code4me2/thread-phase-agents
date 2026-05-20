# thread-phase-agents — moved

This package has been folded into the [`thread-phase` monorepo](https://github.com/Code4me2/thread-phase) and renamed.

| Was | Is now |
|---|---|
| `thread-phase-agents` (this repo) | [`@autonome-research/thread-phase-agents`](https://github.com/Code4me2/thread-phase/tree/master/packages/thread-phase-agents) |
| `github:Code4me2/thread-phase-agents` | `github:Code4me2/thread-phase` (monorepo, `packages/thread-phase-agents/`) |

## What to do

```sh
npm install @autonome-research/thread-phase-agents @autonome-research/thread-phase
```

Update imports:

```diff
- import { claudeCodeAgent } from 'thread-phase-agents';
+ import { claudeCodeAgent } from '@autonome-research/thread-phase-agents';
```

This repo is archived. Issues and PRs for the adapters now belong on [`Code4me2/thread-phase`](https://github.com/Code4me2/thread-phase).

The full pre-monorepo history of this package is preserved inside the monorepo via `git filter-repo` — every old commit is reachable from `master` under `packages/thread-phase-agents/`.
