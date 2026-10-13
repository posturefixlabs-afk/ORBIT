# ORBIT // Real-Life Hunter System

ORBIT is a mobile-first, offline-first life RPG inspired by the feeling of a Hunter System. It turns real actions into measurable progression across fitness, study, habits, discipline, and personal missions.

## Implemented in the current build
- Cinematic Shadow Monarch-inspired dark violet UI with mobile navigation and responsive layouts
- E-to-S Hunter Rank ladder based on lifetime XP, separate character levels, and visible attribute stats
- Daily quests for training, study, and habit consistency
- Adaptive no-equipment workout plan that scales from profile experience, available time, goals, and completed sessions
- Workout completion logging with one reward per day
- Study focus timer; XP is awarded only when a focus block completes
- Habit protocols with one-time daily XP rewards
- Custom personal missions with one-time completion rewards
- Achievements, recent activity log, session count, and rank registry
- Local persistence with JSON export/import and reset controls
- Service-worker app-shell caching for offline use

## Current limits — transparent by design
- This is a client-side web app. Progress is stored in this browser on this device; it is not synced across devices.
- AI coaching is not connected yet. The current workout adaptation is rule-based and runs offline.
- Study timer completion requires the page to remain active enough for the browser to run its timer; it is not a guaranteed background timer.
- Background reminders and reliable scheduled notifications are not implemented yet.
- Rank thresholds and attributes are game mechanics, not medical or fitness measurements. Workouts are general guidance; scale or stop when needed.

## Publish on GitHub Pages
Open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, and save. After the site is published over HTTPS, open its Pages URL in Android Chrome and choose **⋮ → Add to Home screen / Install app**.

## Privacy and safety
No AI API key is embedded in this repository. Do not commit private API keys. A future AI integration should use a secure backend or an explicitly configured endpoint with appropriate safeguards.

## Next milestones
1. Publish and test the current build on Android.
2. Add optional reminders and a robust backup flow.
3. Add secure AI coaching and genuinely adaptive training recommendations.
4. Add deeper analytics, skills, unlockable titles, and polished level-up sequences.
