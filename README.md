# Codex Cloud

This repository is a small experiment space for comparing the Codex Cloud coding interface against the usual OpenClaw workflow through Telegram and the local workspace.

The first goal is simple:

- give Codex Cloud a clean repository to modify;
- keep the project lightweight enough that changes are easy to inspect;
- compare coding quality, autonomy, speed, friction, and compute cost;
- learn whether this route is useful for Christopher and OpenClaw's broader build process.

## Starting Surface

The repository begins with a single static HTML page:

- `index.html`

There is no framework, build system, or package manager yet. That is intentional. Future changes should add complexity only when the experiment actually needs it.

## Experiment Questions

- Does Codex Cloud handle small repo changes cleanly?
- Does it make better or worse implementation choices than OpenClaw's normal local workflow?
- Is the review/edit loop faster or slower?
- Does it reduce compute or operational friction?
- What kinds of tasks should stay in OpenClaw, and what kinds should move to Codex Cloud?

## Current Status

Seed repo created for the first Codex Cloud handoff.
