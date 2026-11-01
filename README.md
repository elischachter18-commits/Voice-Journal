# Voice Journal

A quiet morning and night voice journal for iPhone. You talk; it transcribes with the iPhone's own speech recognition, Claude tidies and organizes your words (no advice, no chat), and everything is saved on your phone only.

Hosted on GitHub Pages next to 200 Lean and Money Tracker.

## Files

| File | What it is |
|---|---|
| `index.html` | The app |
| `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` | Home-screen name and the yellow wheat icon |
| `sw.js` | Lets the app open with no signal |

## On your iPhone
1. Open `https://elischachter18-commits.github.io/Voice-Journal/` in **Safari**, tap **Share > Add to Home Screen**.
2. Open it from the home-screen icon (always use the icon: Safari and the icon keep separate storage).
3. **Settings > Claude key**: paste an API key from console.anthropic.com and tap **Save key**, then **Test it**.
4. The first time you tap the mic, allow microphone and speech recognition.

If voice recognition isn't available, tap **Type instead** and use the microphone on the keyboard.

## Your data
Saved on the phone only. Use **Settings > Download backup** now and then; **Restore backup** brings it back on a new phone.

## Updating
Upload the changed files to the same repository. The app picks up the new version the next time it opens.
