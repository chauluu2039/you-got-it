# Châu · Daily Thriving Dashboard

A personal daily dashboard for growth, reflection, and intentional living — built for an INFJ Advocate.

## Features

- **Today** — daily greeting, quote of the day, habit tracker, mood check-in, growth pillar self-rating, and an INFJ daily reminder
- **Calendar** — monthly view with dots marking days you've written journal entries
- **Journal** — private reflections with mood tags and rotating INFJ writing prompts
- **INFJ Guide** — full reference: strengths, blind spots, do/avoid rules, suggestions, and watch-outs
- **Settings** — export/import your data as JSON, view stats, and install as a PWA
- **Offline support** — works without internet once loaded (service worker)
- **Install as app** — add to your phone or desktop home screen

## Deploy to GitHub Pages

1. **Create a repository** on GitHub (e.g. `chau-dashboard`). Set it to Public.

2. **Upload all 5 files** to the root of the repository:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`

3. Go to **Settings → Pages** in your repository.
   Set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
   Click **Save**.

4. After ~1 minute, your site is live at:
   ```
   https://YOUR-USERNAME.github.io/chau-dashboard/
   ```

## Install as a mobile app

1. Open the live URL in **Chrome** (Android) or **Safari** (iPhone)
2. Android: tap the three-dot menu → **"Add to Home Screen"**
   iPhone: tap the Share icon → **"Add to Home Screen"**
3. The app installs with its own icon and runs fullscreen, offline

## Data & privacy

All data (journal entries, moods, pillar ratings, habits) is stored in your **browser's localStorage** — it never leaves your device and is never sent anywhere. Use the **Export** feature in Settings to back up your data as a JSON file, especially before clearing browser data or switching devices.

---

Built with care. No frameworks, no tracking, no servers.
