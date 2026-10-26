# A+ Core 1 Study App (Independent)

Mobile-first, offline-capable study app for CompTIA A+ Core 1 (220-1201). Not affiliated with or endorsed by CompTIA. CompTIA and A+ are trademarks of CompTIA, Inc.

## Features
- 517 glossary cards and five study domains
- Reduntify: alternate explanation, reverse retrieval, examples, and application practice
- Listen & Learn: 3, 5, or 10 repeats using browser speech synthesis, followed by recall
- Flashcards, multiple-choice quizzes, typed recall, progress tracking and JSON backup/restore
- 90 original written-response troubleshooting practice scenarios (not official performance-based simulations)
- No account, analytics, API keys, or server-side data collection

## Run locally
```sh
python3 -m http.server 8903
```
Open http://127.0.0.1:8903 . To deploy, serve these files from a static HTTPS website.

## Privacy and offline support
Progress is stored in browser localStorage for each site origin; it does not sync automatically. Back it up before switching devices or domains. On iOS, browser speech playback may pause when the screen is locked.

## Limitations
This is independent educational material, not an official exam product, score predictor, or a substitute for objective-based hands-on practice. The 12 scenarios are open-ended written drills, not drag-and-drop PBQ simulations. Quiz grading is limited, and Reduntify self-assessment is self-reported.

## Publishing note
Third-party practice questions supplied privately are deliberately excluded from this public package pending reuse permission. No license grant for reuse of this project's source or content is implied at present.
