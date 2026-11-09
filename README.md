# Pocket Critters v3.8 — Student Launch & Pet Passport

This is the complete game. Upload `index.html` and the **entire `assets` folder** together to replace the previous version. No code editing required.

## What changed in v3.8
- Pet Passport: in Options, save a small JSON file containing all up to three pets, saved growth, discoveries, learning history, and sound setting.
- Restore on a different device using "Restore my Pet Passport" in the Hatching Meadow, or Options > Pet Passport on a device with an existing pet.
- Import requires confirmation and attempts a safety backup of existing local pets before replacing them. Files stay on the device, not sent to any server.
- The game recognizes the Hub's hidden-game unlock flag when opened on the same origin, so importing a Passport also unlocks the visible Hub launcher on that browser.
- No automatic cross-device sync: keep the most recent Passport in approved storage. Sharing the same browser profile shares local saves.

## Prior changes carried forward from v3.7.2
- Added a small, live **daily growth tracker** that shows four minutes of active-care time, completed care, and completed learning/exploring. It does not count sleeping time or teacher gallery previews.
- The Journal now shows how many completed care days remain before the next form (without spoiling its name).
- The Care menu's sleep status updates while it remains open; the main sleep countdown continues beneath the LCD, including after you reopen the tab.
- Sleeping companions are now protected from inactivity penalties during long rest periods, and their last-active clock resumes when they wake.
- Care routines cannot be bypassed from keyboard shortcuts during sleep or caretaker coverage.
- Comforting a companion gives its small joy benefit once per day, instead of allowing unlimited clicks.

## Sleep behavior (unchanged)
- Care > Tuck in starts an eight-hour saved rest goal. The rest timer continues when the browser is closed.
- Early waking is allowed without an additional penalty. It gives +5 energy per elapsed hour (up to +40 for 8 hours). A full rest also earns +5 joy. It never reduces energy.
- A pet remains peacefully asleep when the timer reaches zero until awakened by the player.

## Existing game preserved
- Ten playable species, five fully animated illustrated families with art assets, six evolution stages, retro audio, Sanctuary for up to three companions, moods, settings, care/quiz/exploration, teacher gallery, and existing saved progress.
- Browser localStorage keys remain unchanged; using the updated game in the **same browser and origin** preserves compatible existing saves.
- Avoid deleting the old site's browser storage. Keep `assets` beside `index.html` and preserve all subfolders and PNG files.
