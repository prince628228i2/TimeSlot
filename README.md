# TimeSlot — GitHub Android Build

## CSV behavior
- Every CSV/TXT upload is **merged with the previously saved data (old + new)**.
- If the same `date + time` appears in a new upload, the new value replaces that exact old value.
- Saved parsed data is restored after closing/reopening the app.
- The original CSV file itself does not need to remain on the phone.

## Build
Push this project to GitHub and run **Actions → Build Android APK → Run workflow**.
The APK is available under the workflow run's **Artifacts** as `TimeSlot-debug-apk`.

Do not put a GitHub Personal Access Token inside the source code or commit it to the repository.
