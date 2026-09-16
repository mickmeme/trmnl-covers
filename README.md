# trmnl-covers

Data source for a TRMNL private plugin that rotates through 90s comic covers.

- `covers.json` — array of covers with metadata + image URLs
- `covers/` — the image files themselves

Plugin polls `https://raw.githubusercontent.com/mickmeme/trmnl-covers/main/covers.json` every 15 minutes and shows a new cover each refresh.
