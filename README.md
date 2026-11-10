# Gymie

A single-file workout tracker (`index.html`) for iPhone Safari. It has no dependencies and works offline.

- Opens straight to today's session. Tap a set to check it off, and use +/− to change the weight.
- Remembers your last weight for each exercise and suggests when to increase it.
- Includes a home screen to pick any session, a live 8:00–9:15 timeline bar, a rest timer, treadmill steps, history, progress charts, a daily streak and an InBody log with photos.
- All data (including InBody photos) stays on your phone. Settings can export CSV files for Numbers, Excel or Google Sheets.

## Use on iPhone
1. Enable GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/root`).
2. Open `https://snowie-cheese.github.io/gymie/` in Safari.
3. Tap Share → **Add to Home Screen**.

To change the workout plan, edit `DEFAULT_PLAN` at the top of the `<script>` in `index.html`. You can also use **Settings → Edit workout plan** in the app.
