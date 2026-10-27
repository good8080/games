# Recipe: Make a Game

This project adapts the simple, single-file GitHub Pages approach from
`github-pages-starter` for making small browser games with a young learner.
No setup or programming experience is needed to get started.

## 1. Start with an idea

In VS Code, open Copilot Chat and run `/make-a-game`. Describe a theme or a
game idea in your own words. You can start with something as short as "a
penguin collecting stars on the moon."

Copilot should suggest a small playable version and help the learner make
choices. The optional [SPEC-TEMPLATE.md](./SPEC-TEMPLATE.md) can help shape an
idea, but it is not required.

## 2. Make one game at a time

Each game lives in its own file under `games/`, for example
`games/moon-penguin.html`. A game contains its own HTML, CSS, and JavaScript,
so it is easy to open, edit, and understand. Copilot adds a link to the game
list in `index.html`.

The project intentionally uses no frameworks, package installs, or build
commands. Open the HTML file in a browser or use VS Code's preview/browser
tools to play it.

## 3. Learn by changing things

Try a game, ask why a piece of code works, and choose a small improvement.
Good first experiments include changing a speed, adding a score, changing a
colour, or adding a new rule. Ask Copilot to explain first if something is
unclear.

## 4. Save checkpoints and share them

Git commits are named checkpoints that make it possible to see how a game
changed over time. Ask Copilot to make small commits for completed steps, with
clear messages such as `Add star collecting` or `Make the game work on touch`.

Commits are saved locally first. A parent should approve before Copilot pushes
them to GitHub. After approval, Copilot can use the normal Git workflow. In
VS Code, **Source Control → Push** or **Sync Changes** sends local commits to
GitHub; the commit history then shows how the game developed.

If GitHub requests a sign-in, ask a parent to help. Never share passwords or
access tokens in Copilot Chat.

## 5. Play and improve

Before calling a game finished, try its controls, restart, and scoring or
ending. If GitHub Pages is enabled for this repository, new commits pushed to
the publishing branch update the site. Ask a parent for help if the game is
not appearing online.
