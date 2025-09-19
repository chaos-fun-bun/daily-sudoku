# Daily Sudoku — Static Web App

This is a single-file Sudoku page that:
- Creates a **daily deterministic puzzle** from `?d=YYYY-MM-DD` and `?level=Medium`.
- Lets players solve it **in the browser**.
- Tracks time and mistakes.
- Creates a **share block** the Discord bot can parse for leaderboards.

## Use
Host `index.html` anywhere (GitHub Pages / Replit).

### URL Parameters
- `d` — date in `YYYY-MM-DD`.
- `level` — `Easy`, `Medium`, `Hard`, or `Expert`.

If omitted, it uses the **current day** from the viewer's device.

## Optional: Auto-post results to Discord
- Create a **Channel Webhook** in your Discord channel and paste it into the web app's webhook field.
- Click **Send now** after solving to auto-post.
- **Note:** Webhooks are public endpoints; rotate if abused.
