# DeutschPath — German A1 Lessons 1–7

A complete **static GitHub Pages website** with the seven completed German A1 lesson summaries, example sentences, grammar tables in notes, scores/corrections, a lesson checklist, and a daily journal.

## Publish on GitHub Pages

1. Create a public GitHub repository, e.g. `german-study`.
2. Extract the ZIP and upload **the files inside `german_a1_site/`** to the repository root. Make sure `index.html` sits at the repository root (not inside another folder).
3. Commit/push the files.
4. Repository → **Settings → Pages** → **Build and deployment** → Deploy from a branch → select `main` and `/ (root)` → Save.
5. Open the Pages URL shown in Settings → Pages, typically `https://YOUR-USERNAME.github.io/german-study/`.

You can also run the site by opening `index.html` locally in a browser (no build step).

## Important: changes are not automatically synced to Git

- Checkboxes, custom notes, and journal entries are saved **in your browser's localStorage**. They are not uploaded to GitHub and are not automatically visible on a different device.
- Use **Export progress** to download a `.json` backup and **Import progress** on another browser/device.
- Publishing the static site does not create an online database; to enable true multi-device sync later, integrate authentication + a backend (e.g. Firebase/Supabase) or a separate hosted data source.
- The 7 lessons and their documented assessment results are included in `lessons.json` and embedded in `app.js` so the site can load locally. To update published lesson content, change both, or ask ChatGPT for a regenerated package and push it to GitHub.

## Files

- `index.html` — home page, lessons, journal, roadmap
- `style.css` — responsive site design
- `app.js` — lesson data, interactions, browser storage, export/import
- `lessons.json` — portable source lesson summaries and scores

## Data privacy

The study content includes no home address or personal identifying profile. Journal entries remain locally in your browser unless you explicitly export/share them. Do not commit exported journal backups to a public repository unless you want them public.

## What is included

Lesson 1: Pronouns + sein; Lesson 2: haben + regular verbs; Lesson 3: articles & genders; Lesson 4: word order; Lesson 5: W-questions; Lesson 6: nominative; Lesson 7: accusative.

Exam target: 4 Dec 2026; curriculum target: 30 Nov 2026. Remaining A1–B1 topics are planned but not represented as completed.
