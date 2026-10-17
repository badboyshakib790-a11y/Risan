# RISAN Premium Tool

Branded launcher package for RISAN.

## Files
- `run.py` — displays the RISAN terminal banner and loads the bundled module.
- `main.cpython-314-aarch64-linux-android.so` — precompiled module from the supplied archive.

## Run in Termux
Open Termux in this folder and run:

```bash
python run.py
```

## Important
The bundled `.so` module is compiled and its internal text, interface, and behavior cannot be reliably rebranded by changing `run.py` or this README. If the old name appears from inside that module, the original source code or a buildable replacement is needed.

## Updating your own GitHub repository
1. Create a repository named `RISAN` on your GitHub account.
2. Upload the files in this folder.
3. When you change files later, upload the updated versions or commit and push the changes.
4. Users who clone the repository will need to pull/download updates to receive them.

Only upload code you own or have permission to redistribute. This package changes the launcher branding only; it does not change account limits or platform behavior.
