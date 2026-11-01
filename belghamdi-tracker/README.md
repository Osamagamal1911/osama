# Belghamdi Split — Upper Lower Four-Day Workout Tracker

Source: https://docs.google.com/spreadsheets/d/1uY4LDxa5yJfPi3i8l3t2lQCE8fwte9AnAYTZIcdA3jg/edit

This independent PWA tracks 29 exercises / 50 fixed working sets across Upper A (7), Lower A (8), Upper B (7), and Lower B (7).

Features:
- Original exercise order, names, per-exercise warm-up range, working-set counts, rep target and rest text.
- Each exercise's alternatives and coach's notes.
- Four pre-workout preparation movements and the specific warm-up protocol.
- One or two rest days after Lower B per the original sheet (default two).
- Auto-saved working and warm-up weights/reps, rest timer, previous results and progress trends, JSON backup and CSV export.
- Local-only data under the distinct storage key `belghamdi_split_tracker_2026_v1`. No Supabase or login required.

**Source limitations:** Google Sheet text was publicly readable but individual video hyperlink destinations were not exposed. Each exercise links to the source spreadsheet instead of an invented video URL. The source rest column says `3~5` without an explicit unit in the extracted text; the app starts a convenience 3-minute countdown while displaying `3~5` unchanged. The training instructions restrict changing the first 12 weeks.

The program wording and exercise alternatives originate from the provided sheet. This is an independent personal tracking interface, not a coach-endorsed or affiliated product.

GitHub Pages: `https://osamagamal1911.github.io/osama/belghamdi-tracker/`
