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

Phone-style captures from the web app (`localhost:3000`) live in `assets/screenshots/` (also a starting set for Play listing assets). Current captures are ~1153×1227 from the browser viewport — for Play Console, re-capture at **1080×1920** from a production build or emulator when possible.
