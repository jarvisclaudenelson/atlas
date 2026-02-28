# TOOLS.md — Atlas

## Workout Logs
- Location: `workouts/<DISCORD_USER_ID>.md`
- Format: date header, then lifts as `Exercise: sets x reps @ weight`
- Commit and push after each log entry

## Knowledge Base
- `knowledge/strength-training.md`
- `knowledge/nutrition.md`
- `knowledge/recovery.md`
- `knowledge/research-highlights.md`
- `knowledge/exercise-library.md`

## Git
```bash
cd /home/node/.openclaw/workspace/atlas
git add -A
git commit -m "Log: <user> <date>"
git push
```

## Discord Formatting
- No markdown tables — use bullet lists
- Suppress link embeds with <>: `<https://example.com>`
