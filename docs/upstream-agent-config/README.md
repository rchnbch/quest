# Upstream agent config, kept as reference only

`electric-capital/quest` ships a root `CLAUDE.md`, `.claude/commands/` and
`.claude/skills/verify/`. The content is useful — dev conventions, the local
`dev_port` / `dev_config.json` detail, and a verify workflow that drives a
local instance via dev-login cookies and playwright.

It is kept here as `.txt` so it is **reference, not instructions**: nothing in
this directory is auto-loaded by an agent session opened in this checkout.
`.claude/` and `CLAUDE.md` stay gitignored at the repo root.

Re-sync these by hand if upstream changes them; a merge will not do it for you.
