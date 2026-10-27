# Make-a-Game

A small, friendly workshop for making original HTML games with GitHub Copilot.
Describe a game idea in your own words, then use the `/make-a-game` prompt in
Copilot Chat to build and learn from it.

## Get started

1. Open this repository in VS Code and sign in to GitHub Copilot.
2. Open Copilot Chat and choose `/make-a-game`.
3. Enter a theme or game idea when prompted.
4. Preview the game, try it out, and ask Copilot to help you improve it.

Games are self-contained HTML files in `games/`. The home page, `index.html`,
will link to each game. No install or build step is needed; the games are
designed to work on GitHub Pages.

## Saving and sharing changes

Copilot can help make clear, small commits so the Git history tells the story
of how a game grew. A commit saves a checkpoint on this computer; pushing sends
those commits to GitHub, where they can be viewed online. Copilot should ask a
parent before pushing. In VS Code, **Source Control → Sync Changes** (or **Push**)
sends committed changes to GitHub.

Never share passwords or access tokens in chat. If GitHub asks to sign in, ask
a parent to help.

## Project files

- [RECIPE.md](./RECIPE.md) explains the game-making and learning workflow.
- [SPEC-TEMPLATE.md](./SPEC-TEMPLATE.md) is an optional idea-planning sheet.
- [.github/copilot-instructions.md](./.github/copilot-instructions.md) gives
  Copilot project-wide guidance.
- [.github/prompts/make-a-game.prompt.md](./.github/prompts/make-a-game.prompt.md)
  is the reusable game-making prompt.
