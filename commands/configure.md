---
description: Set your location, favorite stores, and preferences
argument-hint: [city, stores, or preferences]
---

Help the user configure their grocer preferences. Read the current config from `~/dev/grocer/config/preferences.md` (create if missing).

Arguments: $ARGUMENTS

If no arguments, ask the user what they'd like to configure using AskUserQuestion with these options:
- Location (city/region)
- Favorite stores (ordered by preference)
- Language preference (for store searches)
- Measurement system (metric/imperial/both)

Update `~/dev/grocer/config/preferences.md` with their choices. Keep the format simple and readable.
