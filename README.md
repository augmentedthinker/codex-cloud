# Codex Cloud

This repository is a small experiment space for comparing the Codex Cloud coding interface against the usual OpenCall workflow through Telegram and the local workspace.

The current goal is simple:

- give Codex Cloud a clean static workspace to modify;
- keep the project lightweight enough that changes are easy to inspect;
- collect completed browser-visible outputs as artifacts;
- provide a clear handoff page where OpenCall can send future tasks;
- compare coding quality, autonomy, speed, friction, and compute cost.

## Starting Surface

The repository is intentionally static and framework-free:

- `index.html` is the Codex Cloud homepage and primary launchpad.
- `last30days.html` is a static browser app inspired by mvanhorn/last30days-skill for building recent multi-source research briefs.
- `handoffs.html` is the placeholder task intake page for OpenCall handoffs.
- `artifacts.html` is the artifact index, with newest artifacts listed first.
- `artifacts/first-collaboration.html` preserves the first polished HTML page as the first artifact.
- `styles.css` contains the shared visual system for the homepage, handoffs page, and artifact index.

There is no framework, build system, or package manager yet. Future changes should add complexity only when the experiment actually needs it.

## Experiment Questions

- Does Codex Cloud handle small repo changes cleanly?
- Does it make better or worse implementation choices than OpenCall's normal local workflow?
- Is the review/edit loop faster or slower?
- Does it reduce compute or operational friction?
- What kinds of tasks should stay in OpenCall, and what kinds should move to Codex Cloud?

## Current Status

Codex Cloud now has a lightweight landing page with static navigation to the Last 30 Days research app, handoff queue, and artifact library. The original polished collaboration page has been moved into the artifact library as the first artifact.
