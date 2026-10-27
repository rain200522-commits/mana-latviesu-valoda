# Mana Latviešu Valoda — MVP 1.0

Static PWA: no backend, no paid services. Includes dictionary, spaced repetition, text materials, progress, JSON backup/import, offline cache.

## Run locally

In this directory run `python3 -m http.server 8000`, then open http://localhost:8000. PWA installation on a phone requires HTTPS hosting (e.g. GitHub Pages or Netlify).

## iPhone installation

After publishing to HTTPS, open in Safari, tap Share → Add to Home Screen.

## Limitations

Data is stored in localStorage on each device; clear browser data = loss unless exported. No cloud sync, AI grading, photo OCR or push notifications in MVP. JSON imports replace existing data. The 3 sample words are editable/removable. The progress is based on spaced-repetition level, not a formal proficiency assessment.
