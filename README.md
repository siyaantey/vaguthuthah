# ވަގުތުތައް (Vaguthuthah)

Prayer times and important days for the Maldives.

**Download:** [Vaguthuthah.apk](https://raw.githubusercontent.com/siyaantey/vaguthuthah/main/Vaguthuthah.apk)

The app checks `update.json` twice a day for new versions and holiday changes.

## Adding a holiday everyone gets
Edit `update.json` and add to `holidays`:
```json
{"date": "2026-12-03", "en": "Extra government holiday", "dv": "ސަރުކާރު ބަންދު"}
```
Put a date in `not_holidays` to cancel a holiday.

## Releasing a new version
Replace `Vaguthuthah.apk`, then raise `versionCode` and `versionName` in `update.json` and write the notes.
