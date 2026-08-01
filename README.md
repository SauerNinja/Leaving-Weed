# Quit THC — a sourced guide

An educational, non-personal resource on quitting cannabis: the real withdrawal
timeline, why it hits certain conditions (ADHD, autism, depression, schizotypal
traits) harder, evidence-based treatment, and how to recover from a single lapse
without losing progress.

Live at: https://sauerninja.github.io/Leaving-Weed/

## Why this exists

A public, sourced resource for anyone dealing with heavy cannabis use and trying to quit —
grounded in real clinical literature instead of guesswork, shame, or vague advice.

## Files
- `index.html` — **the main page.** General, sourced info on THC withdrawal, why severity varies, and what treatment actually works. This is what's meant to rank in search and get shared.
- `journal.html` — an optional day-by-day journal template that any visitor could use to track their own quit (timeline, day counter). Not indexed by search engines; it's a tool, not a record of anyone in particular.
- `404.html` — branded not-found page, shown if someone hits a broken or old link, with a way back to the guide.
- `LICENSE` — MIT license
- `robots.txt` / `sitemap.xml` — search engine crawling and indexing configuration
- `.nojekyll` — an empty file that tells GitHub Pages to skip its default Jekyll build step, since this site doesn't need it. **Note:** it's a dotfile, so it won't show in a plain `ls` — use `ls -la` to confirm it's there, and make sure your file browser shows hidden files before pushing.
- `favicon.ico`, `favicon-16.png`, `favicon-32.png`, `apple-touch-icon.png`, `icon-512.png`, `og-image.png` — site icon and social share image, in the sizes browsers and platforms expect.

## Sources
All claims on `index.html` are attributed inline, with a full reference list
at the bottom — real, checkable clinical literature. Feel free to share the
link directly to any section (each has an anchor, e.g. `index.html#treatment`).

## Publishing to GitHub Pages
1. Push these files to the `SauerNinja/Leaving-Weed` repo:
   ```bash
   git init
   git add index.html journal.html 404.html README.md LICENSE robots.txt sitemap.xml .nojekyll favicon.ico favicon-16.png favicon-32.png apple-touch-icon.png icon-512.png og-image.png
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/SauerNinja/Leaving-Weed.git
   git push -u origin main
   ```
2. Settings → Pages → Source: "Deploy from a branch," `main`, `/ (root)` → Save
3. Live at `https://sauerninja.github.io/Leaving-Weed/`

To post an update later: edit the file, then `git add`, `git commit -m "update"`, `git push`.

## License
MIT — see `LICENSE`. Use, adapt, and redistribute freely, with attribution
appreciated but not required.

## If you're reading this because it applies to you
A website can explain mechanisms. It can't replace a doctor, a therapist, or
a crisis line. If any part of this resonates and things feel unmanageable,
please reach out to a professional, or in the US, call or text 988.
