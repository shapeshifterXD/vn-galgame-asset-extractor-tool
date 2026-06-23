# Quick Start — Vn

## Before you begin

- Use copies of game data — never work on your only backup.
- Confirm you have rights to inspect the assets you process.

## Steps

1. Open **Releases** and download the latest Windows package.
2. Extract the archive to a folder you control.
3. Launch the application from the release folder (double-click the main binary).
4. Set **Input** to your game directory or dropped archive.
5. Choose an export preset matching `VN / galgame asset extractor`.
6. Set **Output** to an empty folder.
7. Click **Start** and wait for the batch job to finish.
8. Open the output folder and verify exported files.

## Tips

- Enable verbose logging in settings when reporting issues.
- Save presets after a successful run to reuse the same pipeline.
- For large folders, run overnight — progress is shown in the UI.

## Troubleshooting

| Issue | Fix |
|---|---|
| Access denied | Run from a user-writable folder, not `Program Files` |
| Empty output | Re-check input path and preset compatibility |
| SmartScreen block | More info → Run anyway, or build from source |
