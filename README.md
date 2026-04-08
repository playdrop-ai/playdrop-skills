# playdrop-skills

Generated public Playdrop legacy skill packages for AI coding agents and developer workflows.

Playdrop helps creators level up their vibe coded games with publishing, hosting, assets, services, and remixable references for the web.

Learn more at [playdrop.ai](https://www.playdrop.ai/).

## Preferred public setup

Use the public Playdrop plugin for the best results.

- Plugin docs: [playdrop.ai/docs/plugin](https://www.playdrop.ai/docs/plugin)
- Canonical public plugin repo: [playdrop-plugin](https://github.com/playdrop-ai/playdrop-plugin)
- Supported plugin environments: Codex, Claude Code, and Cursor

This `playdrop-skills` repo is still supported, but only as a legacy compatibility and skills.sh surface.

## Source of truth

This repo is sync-only and legacy-first.

- Canonical public source: [playdrop-plugin](https://github.com/playdrop-ai/playdrop-plugin)
- Generated compatibility and skills.sh surface: `playdrop-skills`

Do not make manual first edits here. Regenerate this repo from the private Playdrop monorepo instead.

## Install

Preferred public setup:

- Install the Playdrop plugin from [playdrop-plugin](https://github.com/playdrop-ai/playdrop-plugin) using your AI tool's plugin install flow

Legacy compatibility install if you still need the old skill model:

```bash
npx skills add https://github.com/playdrop-ai/playdrop-skills --skill playdrop
```

Regenerate from the private PlayDrop monorepo root with:

```bash
node scripts/sync-legacy-skills-repo.mjs
```

## What Playdrop provides

- Hosting with shareable game listings and social features such as follow, like, save, and comments
- Online services for identity, saves, multiplayer, monetization, and AI generation
- A catalogue you can browse and remix for code samples, 3D, images, animations, music, SFX, and video

## Current skills

- `skills/playdrop`: umbrella compatibility skill
- `skills/task-routing`
- `skills/game-planning`
- `skills/scope-control`
- `skills/gameplay-mockups`
- `skills/asset-discovery`
- `skills/project-updates`
- `skills/dev-testing`
- `skills/game-improvement`
- `skills/gameplay-review`
- `skills/store-listing`
- `skills/comment-monitoring`
- `skills/game-marketing`
- `skills/service-integration`
- `skills/engine-porting`
- `skills/creator-support`

## Scope

- This repo is for public Playdrop creator and developer workflows
- Canonical plugin changes happen in `playdrop-plugin`
- Legacy sync is maintained from the private `playdrop` monorepo
- Skills should prefer public Playdrop documentation and stable CLI commands
- Non-public platform operations are out of scope
