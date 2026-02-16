# rx-space

This repository is currently a scaffold.

## Current Status

- There is no runnable app code in this repo yet.
- The only tracked project file right now is this `README.md`.
- If you expected source files, your clone is likely fine; the project just has not been initialized.

## Quick Reality Check

Run these commands from the repo root:

```bash
pwd
git branch --show-current
git status
ls -la
```

Expected outcome:

- You are inside `rx-space`.
- You are on your intended branch (usually `main` unless told otherwise).
- `git status` is clean unless you made edits.
- File listing is minimal.

## Common Failure Modes

1. Wrong folder
   You are in a parent directory, not the repo root.
2. Wrong branch
   You checked out a branch that does not contain app code.
3. Wrong expectation
   The app has not been scaffolded or pushed yet.

## If You Want a Working App Here

Pick one stack and scaffold it in this repo, for example:

```bash
# Next.js example
npx create-next-app@latest .
```

Then:

```bash
npm install
npm run dev
```

## Safety Checklist Before Committing

- Confirm secrets are not committed (`.env`, API keys, tokens).
- Confirm generated files are ignored where appropriate.
- Confirm the app builds and runs locally.
- Commit in small, reviewable chunks.
