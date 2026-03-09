# Reminder App

A personal reminder app that lives on your iPhone home screen. Type or speak reminders, view them grouped by urgency, mark them done.

## Adding to iPhone home screen

1. Open your GitHub Pages URL in Safari
2. Tap the Share button (box with arrow pointing up)
3. Tap "Add to Home Screen"
4. Tap "Add" — the app icon will appear on your home screen

## How to use

- **Add a reminder:** Type in the text box and tap "Add Reminder"
- **Voice input:** Tap the mic key on your iPhone keyboard to speak a reminder
- **Due date:** Optionally pick a date before adding
- **Mark done:** Tap the checkbox next to a reminder
- **View completed:** Tap "Show completed" at the bottom

Reminders are sorted automatically: overdue first (shown in red), then today, then upcoming, then undated.

## Hosting on GitHub Pages (free)

1. Create a new repository on GitHub (e.g. `my-reminders`)
2. Upload `index.html` to the repository
3. Go to **Settings → Pages**
4. Under "Source", select: **Deploy from a branch → main → / (root)**
5. Your app will be live at: `https://your-username.github.io/my-reminders/`

## Data & privacy

All data is stored in your browser's localStorage. Nothing is sent to any server. Clearing your browser data will erase your reminders.

To back up your reminders, open the browser console (long-press the address bar in Safari → Inspect) and run:

```js
localStorage.getItem('reminders')
```

Copy the output and save it somewhere safe.
