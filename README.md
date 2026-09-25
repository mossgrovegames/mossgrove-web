# mossgrove-web

Public website of Mossgrove Games, served by GitHub Pages at https://mossgrovegames.com.

- `index.html` – studio landing page
- `privacy/index.html` – privacy policy for all Mossgrove Games titles (PL/EN, language switch)
- `CNAME` – custom domain for GitHub Pages

Static files only. No game code, no keys, no paid assets belong here.

## Changing the privacy policy

1. Edit `privacy/index.html` in both languages (the `#pl` and `#en` sections carry the same 12 numbered sections).
2. Bump the "ostatnia aktualizacja" / "last updated" date in both languages.
3. Commit and push to `main`. GitHub Pages publishes by itself within about a minute; check
   https://mossgrovegames.com/privacy/.
4. In every game: bump `LocalConsent.Version` so players are asked again, and keep the game's Data safety answers
   (`Docs/data-safety.md`) in step.

This clone (`C:/WORKSPACE/Projects/Mossgrove/MossgroveWeb`) is the only copy of the website; games keep none.
