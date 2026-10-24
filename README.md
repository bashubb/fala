# Fala website

Static site for `https://bashubb.com/fala/`: a coming-soon page, the privacy policy and support for App Store Connect. Publish the `docs/` folder of the GitHub repository `bashubb/fala` with GitHub Pages (Settings → Pages → main, /docs; leave Custom domain empty — the account's `bashubb.com` serves it under `/fala/`).

```sh
python3 -m http.server 8790 --bind 127.0.0.1 --directory docs
```

App source: `../../Fala/`. Facts on the pages (techniques and rhythms, 8 programs with First week free, iOS 17+, English and Polish, Apple Health write-only mindful minutes in Premium, free night mode / widgets / reminders, no network, no account) come from the code — re-check them when those change.

Shared landing system: `docs/assets/landing.css` and `landing.js` are identical across Wipe, Ringbox, Tempo and Fala; site colours live in `fala.css` (the app's palette). iPhone mock-ups: real iPhone 17 Pro Max bezel flattened with `fronts.py`, screens from the app in English (simulator, debug launch arguments listed in `../../Fala/AppStore/README.md`). Subpages were rebuilt with `subpages.py docs fala.css privacy support`.

No film yet: on phones the page opens with the hero instead of `.film-intro`. Once a vertical film exists, add the `film-intro` / `film-sec` sections like Ringbox.
