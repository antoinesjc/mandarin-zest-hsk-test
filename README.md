# Mandarin Zest: quick HSK level test

Live at https://antoinesjc.github.io/mandarin-zest-hsk-test/ (embedded on
mandarinzest.com/quick-hsk-level-test).

- `index.html`: the test. Settings at the top of the script: number of
  questions, start level (everyone starts at HSK 2), links, shop tag numbers per
  level, grammar sentences, "I can…" lines per level.
- `words.js`: the word bank (HSK 1–3: 50 words each, HSK 4–6 and 7–9: 100 each).
- `mascot-reading.png`: the mascot.

How it works: 25 adaptive questions mixing vocabulary, listening (the browser's
built-in Chinese voice; skipped if the device has none), reading and grammar.
Two right answers in a row → one level up; a miss or a skip → one level down.
The result is the highest level answered at least 60% right. The result screen
shows skills, a shareable 1080×1350 image, the Club (HSK 2+) or the free Start
Here guide (HSK 1), the shop filtered by level, and an optional email sign-up
(saved to the Start Here Google Sheet with source "hsk-test | <level> | <score>").
All links open in a new tab.
