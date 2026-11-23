# The Daily Chai

A daily five-minute digest of B2B tech news, written for someone learning B2B product marketing. Each story has a plain-English summary and a takeaway, plus a quote of the day from a founder, CEO or investor.

- `editions/YYYY-MM-DD.json`: one file per day (quote, term of the day, 10 stories, sources). Each story has `addons`: any of "sweet" (good news), "iced" (money: funding, deals, pricing, spend) and "hot" (newest, broke in the last day). The first 4 stories show; the rest are poured in with "Pour me another".
- `editions/index.json`: list of edition dates, newest first. The app opens the first one.
- `index.html`: the app (Today, Past cups, Saved). Saved stories are kept on the phone.
- `manifest.json`, `sw.js`, `icons/`: make it installable ("Add to Home Screen") and readable offline.

Hosted with GitHub Pages. A new edition is added every morning at 7:12 AM Pacific.
