# Quit THC — a sourced guide

An educational, non-personal resource on quitting cannabis: the real withdrawal
timeline, why it hits certain conditions (ADHD, autism, depression, schizotypal
traits) harder, evidence-based treatment, and how to recover from a single lapse
without losing progress.

Live at: https://sauerninja.github.io/quit-thc-leave/

## Why this exists

I've dealt with this myself, and writing it out — grounded in real sources
instead of guesswork or shame — has helped me. I'm sharing it publicly in
case it's useful to someone else working through the same thing.

## Files
- `index.html` — **the main page.** General, sourced info on THC withdrawal, why severity varies, and what treatment actually works. This is what's meant to rank in search and get shared.
- `journal.html` — an optional personal day-by-day log template (timeline, day counter). Not indexed by search engines; edit freely if you want to keep a public log alongside the main page, or ignore it.
- `LICENSE` — MIT license
- `robots.txt` / `sitemap.xml` — search engine configuration

## Sources
All claims on `index.html` are attributed inline, with a full reference list
at the bottom — real, checkable clinical literature. Feel free to share the
link directly to any section (each has an anchor, e.g. `index.html#treatment`).

## Publishing to GitHub Pages
1. Push these files to the `sauerninja/quit-thc-leave` repo:
   ```bash
   git init
   git add index.html journal.html README.md LICENSE robots.txt sitemap.xml
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/sauerninja/quit-thc-leave.git
   git push -u origin main
   ```
2. Settings → Pages → Source: "Deploy from a branch," `main`, `/ (root)` → Save
3. Live at `https://sauerninja.github.io/quit-thc-leave/`

To post an update later: edit the file, then `git add`, `git commit -m "update"`, `git push`.

## License
MIT — see `LICENSE`. Use, adapt, and redistribute freely, with attribution
appreciated but not required.

## If you're reading this because it applies to you
A website can explain mechanisms. It can't replace a doctor, a therapist, or
a crisis line. If any part of this resonates and things feel unmanageable,
please reach out to a professional, or in the US, call or text 988.
