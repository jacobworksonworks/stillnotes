# Still — Notes

A local-first writing app with a compact dark interface. No account, analytics, or external runtime libraries.

## Run it

Open `index.html` for local use. For installability and offline caching, serve the folder from a secure origin (HTTPS or localhost); service workers do not run from ordinary `file://` URLs.

## Included

- Multiple notes with local autosave, snapshots, import, TXT and HTML export
- Markdown preview and a separate side-by-side Markdown tool
- Writing stopwatch, Pomodoro timer, focus mode and fullscreen support
- Writing statistics, break reminders, and typewriter key sound
- Preferences for font family, font size, line width, spellcheck and tab indentation
- Text tools, case converter, Unicode symbol picker and text comparison
- Rich-text scratch editor, teleprompter, drawing pad and voice recording
- Kanban board, tasks, and multiple scratch notes
- Generated ambient noise mixer
- Native share and floating-window support where the browser provides those APIs
- PDF output through the browser print dialog
- PWA manifest and offline service worker

## Storage and limitations

Notes, tasks, snapshots, preferences, Kanban cards and scratch notes are stored in the current browser's local storage. Clearing browser data clears those records, so export backups when needed. Voice recordings are downloadable from the recording session; they are not retained as a persistent media library. PDF uses the browser's print dialog. DOCX export, a full library of recorded ambient tracks, task due-date reminders, and every original preference/texture/effect are not yet implemented.
