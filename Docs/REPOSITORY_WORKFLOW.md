# COPYROOM Repository Workflow

## Everyday cycle

1. `git switch main`
2. `git pull --ff-only`
3. `git switch -c feature/<short-name>`
4. Work in Unreal and save deliberately.
5. Close Unreal before reviewing large asset changes.
6. `git status`
7. `git add <specific paths>`
8. `git diff --cached --stat`
9. `git commit -m "feat: describe the completed change"`
10. Test the packaged build when the feature requires it.
11. Merge the feature branch into `main` only when playable.
12. `git push`

## Commit prefixes

- `setup:` project/repository configuration
- `feat:` new gameplay or content capability
- `fix:` bug correction
- `art:` model, material, environment, or VFX work
- `audio:` sound and MetaSound work
- `ui:` interface and UX work
- `perf:` optimization
- `build:` packaging and platform configuration
- `docs:` documentation only
- `test:` automated or manual test infrastructure

## Golden rule

A commit should represent one understandable change that can be reverted without dragging unrelated work with it.
