---
name: playdrop
description: "Compatibility Playdrop skill for public creator workflows. Use this when working from the legacy playdrop-skills repo or skills.sh distribution and you need a broad public Playdrop workflow across planning, improvement, publishing, services, references, and ongoing project management."
---

# Playdrop

This is the legacy compatibility skill package generated from the canonical `playdrop-plugin` repo.

- Canonical source: `https://github.com/playdrop-ai/playdrop-plugin`
- Legacy compatibility surface: `https://github.com/playdrop-ai/playdrop-skills`
- Synced platform version: `0.5.5`

Use this skill when you only have the umbrella `playdrop` skill installed from the legacy skills repo and need the broad public Playdrop workflow.

## First steps

1. Install the CLI: `npm install -g @playdrop/playdrop-cli`
2. Log in: `playdrop auth login`
3. Initialize: existing project -> `playdrop project init .` ; new project -> `playdrop project create app <name> --template <ref>`
4. Validate: `playdrop project validate .`

## Use this skill when

- you need to plan a new Playdrop game
- you need to cut scope before implementation
- you need gameplay mockups or a candid gameplay review
- you want to inspect references, assets, or starter kits
- you need help improving an existing game before publish
- you need store listing guidance
- you want to integrate services like auth, saves, realtime, monetization, or AI assets
- you need the legacy broad Playdrop workflow rather than a more specific skill

## Recommended specialist skills

If the environment supports installing more specific skills from the same legacy repo, prefer:

- `game-planning`
- `scope-control`
- `gameplay-mockups`
- `asset-discovery`
- `project-updates`
- `dev-testing`
- `game-improvement`
- `gameplay-review`
- `store-listing`
- `comment-monitoring`
- `game-marketing`
- `service-integration`
- `engine-porting`
- `creator-support`

## Shared references

Use the local `references/` files in this legacy package when you need more detail:

- `cli-map.md`
- `discovery.md`
- `pitch-and-validation.md`
- `scope-cutting.md`
- `gameplay-mockups.md`
- `gameplay-review.md`
- `existing-projects.md`
- `create-and-remix.md`
- `godot-porting.md`
- `racing.md`
- `platformer-3d.md`
- `fps.md`
- `services.md`
- `assets-and-generation.md`
- `audio.md`
- `publish-and-listing.md`
- `live-ops.md`
- `performance-debugging.md`

## Rules

- prefer public Playdrop docs and stable CLI commands
- use `playdrop documentation browse` and `playdrop documentation read <path>` when you need the latest product guidance
- keep guidance focused on public creator workflows
- if a more specific generated skill is installed, hand off to it rather than keeping everything in this umbrella flow
