---
name: playdrop
description: "Use this skill for Playdrop, an AI gaming platform and public CLI/SDK for improving, publishing, and managing web games, apps, and assets. Use it when you want shareable distribution, better visuals or audio from catalog or AI-generated assets, code references from published demos, or online services such as identity, saves, multiplayer, and monetization."
---

# Playdrop

Playdrop is an AI gaming platform that helps level up vibe-coded web games.
Use this skill to improve, publish, and manage your web game, app, or asset.

## First steps

1. Install : `npm install -g @playdrop/playdrop-cli`
2. Log In : `playdrop auth login`
3. Overview : `playdrop getting-started`
4. Initialize : existing project -> `playdrop project init .` ; new app -> `playdrop project create app <name> --template <ref>`

## Use this skill when

- want to make a game prettier with Playdrop catalog assets or AI generation for images, video, 3D, music, and SFX
- want to add identity such as usernames and avatars, or persistence such as game saves
- want to reuse code references from published Playdrop games or demos to build features faster and with less risk
- want to make a game realtime multiplayer
- want to publish a game on the playdrop platform so that people can find it and play it
- want to add monetization with IAP to a game
- want to manage an existing game by reviewing comments, release history, listing updates, and new releases

## Explore references

- Browse : `playdrop browse ...`
- Search : `playdrop search <query>`
- Inspect : `playdrop detail <ref> --json`
- Docs : `playdrop documentation browse` and `playdrop documentation read <path>`
- Inspect 2 to 3 strong references before changing art, controls, systems, or packaging.
- Command map : see `references/cli-map.md`
- See `references/discovery.md`

## Existing projects

- Initialize in place : `playdrop project init .`
- Check project metadata, typically `catalogue.json`
- Validate : `playdrop project validate .`
- When the user says use `$playdrop`, assume registration and reference research are in scope unless they narrow the task.
- See `references/existing-projects.md`

## Create or remix

- New app : `playdrop browse --kind app --app-type template --json` then `playdrop project create app <name> --template <ref>`
- Remix : `playdrop project create app <name> --remix <ref>`
- Prefer remix when a public starter or demo is already close to the requested project.
- See `references/create-and-remix.md`

## Porting shortcut

- Godot or engine port : inspect `playdrop/app/starter-kit-racing` and `playdrop/app/starter-kit-3d-platformer` early.
- Use them as the default references for source freezing, scene conversion, debug hooks, hosted validation, and mobile parity unless there is a better fit.
- If you choose not to use them, say why.
- See `references/godot-porting.md`

## Genre shortcut

- Racing, kart, or vehicle game : inspect `playdrop/app/starter-kit-racing` early.
- Use it as the default reference for art, controls, physics, camera, HUD, and mobile controls unless there is a better fit.
- 3D platformer or third-person character controller game : inspect `playdrop/app/starter-kit-3d-platformer` early.
- Use it as the default reference for movement, orbit camera, jump and landing behavior, collectibles, falling platforms, debug hooks, and mobile controls unless there is a better fit.
- If you choose not to use it, say why.
- See `references/racing.md`
- See `references/platformer-3d.md`

## Services

- Playdrop services include identity, avatars, saves, realtime multiplayer, monetization, and AI generation.
- Read public docs first, then integrate only what helps the project.
- See `references/services.md`

## Assets

- Playdrop catalog content can include code samples, 3D, images, video, music, and SFX.
- Start with `playdrop browse`, `playdrop search`, and `playdrop detail`.
- See `references/assets-and-generation.md`

## Capture and publish

- Capture proof : `playdrop project capture` or `playdrop project capture remote`
- Validate : `playdrop project validate .`
- Publish : `playdrop project publish .`
- For listing-heavy tasks: capture gameplay first, then screenshots, hero, icon, then publish.
- See `references/publish-and-listing.md`

## Manage live projects

- Use Playdrop creation, comment, version, and publish tools to manage releases and community activity.
- Use this when reviewing comments, preparing metadata updates, or shipping a new release.
- See `references/live-ops.md`

## Rules

- Prefer public docs and stable CLI commands over undocumented workflows.
- If docs browsing fails, continue with `playdrop help`, `playdrop getting-started`, `playdrop browse`, and `playdrop detail`.
- Do not rely on unpublished docs, local repo paths, or non-public workflows.
- Use `playdrop project capture` or `playdrop project capture remote` when a screenshot, runtime log, or browser proof is needed.
- Keep guidance focused on public creator and developer workflows.
