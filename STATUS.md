# Status — 2026-11-01

## Working
- Head-less suites pass: `tests/run` exits 0, run today (store 108, QML 14, keys, paste 25, gc 27, setup 15, copy 16 checks).
- Installed and bound: `~/.config/omarchy/plugins/leonrlr4.days` is a checkout of this same commit `997cecb`, and `SUPER + M` toggles it in `bindings.lua`. Checked the files today, not the overlay on screen.

## Unverified
- The overlay itself (calendar events through the Google Calendar plugin's bridge, clipboard paste, join/map links): not looked at in this session.
- The user's own bar widget `arnaud.days`, which opens this overlay, lives outside this repo and was not checked.

## Next
- Decide whether to keep this fork: it has no commits of its own and matches upstream `leonrlr4/days` at `997cecb`.

## Evidence
- [README.md](README.md) (install, setup, keys), [design spec](docs/decisions/specs/2026-09-11-daily-task-overlay-design.md).
- GitHub fork of `leonrlr4/days`; issues are disabled; no PRs; no CI.
