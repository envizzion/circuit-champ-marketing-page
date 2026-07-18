# Circuit Champ marketing site

Static GitHub Pages site for **Circuit Champ 2** (Envizzion): landing page, privacy policy, and support.

## Pages

| Path | Purpose |
|------|---------|
| `/` | Landing + screenshot gallery |
| `/privacy/` | Privacy policy (Play Console URL) |
| `/support/` | Support page (Play Console URL) |

## Local preview

```bash
# from this directory
python3 -m http.server 8080
# open http://localhost:8080
```

## GitHub Pages

1. Create a GitHub repo and add it as `origin`.
2. Push `main`.
3. **Settings → Pages →** Deploy from branch `main`, folder `/` (root).
4. Use these URLs in Play Console (replace user/repo):

   - Privacy: `https://<user>.github.io/<repo>/privacy/`
   - Support: `https://<user>.github.io/<repo>/support/`

Links are relative so the site works under a project Pages base path.

## Screenshots

Mobile captures live in `assets/screenshots/`:

| File | Screen |
|------|--------|
| `01-sandbox-live-simulation.png` | Sandbox with powered bulb + current flow |
| `02-training-workshop.png` | Training component workshop |
| `03-ranked-levels.png` | Ranked levels list |
| `04-multimeter-live-readings.png` | Voltmeter + ammeter readings |
| `05-component-library.png` | Component palette overview |
| `06-challenge-ohms-law.png` | Challenge with Ohm’s Law panel |
| `07-my-circuits-cloud-saves.png` | My Circuits local/cloud saves |
| `08-profile-progress.png` | Profile stars, streaks, achievements |

For Play Console, prefer **1080×1920** exports when re-capturing.
