# COPYROOM

Stylized first-person production comedy and corporate horror game.

## Technical baseline

- Engine: Unreal Engine 5.7.4
- Project: `Project/COPYROOM_Proto/COPYROOM_Proto.uproject`
- Primary platform: Windows x64
- Repository model: Git + Git LFS
- Current milestone: Prototype v0.1

## First-time setup

1. Install Unreal Engine 5.7.4.
2. Install Git and Git LFS.
3. Run `git lfs install` once on the machine.
4. Clone the repository and run `git lfs pull`.
5. Open `Project/COPYROOM_Proto/COPYROOM_Proto.uproject`.

## Rules

- Do not open or resave the project in another Unreal Engine version.
- Do not commit `Binaries`, `DerivedDataCache`, `Intermediate`, `Saved`, or packaged builds.
- Move and rename Unreal assets inside the Content Browser, not Windows Explorer.
- Record every shipped AI-assisted asset in `Docs/AI_Asset_Ledger.csv`.
- Keep `main` in a playable, packageable state.
